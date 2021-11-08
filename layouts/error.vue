<template>
  <v-app dark>
    <v-container class="fill-height">
      <v-row align="center">
        <v-col v-if="error.statusCode === 404" cols="12" align="center">
          <h1>
            {{ pageNotFound }}
          </h1>
        </v-col>

        <v-col v-else cols="12">
          <h1>
            {{ otherError }}
          </h1>
        </v-col>
        <v-col cols="12" align="center">
          <v-btn rounded color="primary" small dark to="/">
            Volver al Inicio
          </v-btn>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>

<script>
export default {
  layout: 'empty',
  props: {
    error: {
      type: Object,
      default: null
    }
  },
  data () {
    return {
      pageNotFound: '404 Not Found',
      otherError: 'An error occurred'
    }
  },
  head () {
    const title =
      this.error.statusCode === 404 ? this.pageNotFound : this.otherError
    return {
      title
    }
  }
}
</script>

<style scoped>
h1 {
  font-size: 20px;
}
</style>
