<template>
  <v-container class="grey lighten-5">
    <v-row>
      <template>
        <v-card class="mx-auto" max-width="344" outlined>
          <v-list-item three-line>
            <v-list-item-content>
              <div class="text-overline mb-4">
                LUIS FELIPE
              </div>
              <v-list-item-title class="text-h5 mb-1">
                WOM MOVIL
              </v-list-item-title>
              <v-list-item-subtitle> 1053812576 </v-list-item-subtitle>
            </v-list-item-content>
            <v-list-item-avatar tile size="130">
              <img
                src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcROjQl2_xlEwQac5-gU46NC3aCqkA2_2LlaHdFv4IGF2TUhihAzn7dLU_xcBRxt0pJQTtc&usqp=CAU

"
                alt=""
              >
            </v-list-item-avatar>
          </v-list-item>

          <v-card-actions>
            <v-btn outlined rounded text>
              9087
            </v-btn>
          </v-card-actions>
        </v-card>
      </template>
    </v-row>
    <br><hr>
    <v-row no-gutters>
      <v-col order="last">
        <v-card
          class="pa-2"
          outlined
          tile
        >
                    <v-card max-width="400" class="mx-auto">
            <v-app-bar dark color="pink">
              <v-app-bar-nav-icon />

              <v-toolbar-title>PLAN LIBERATE XL</v-toolbar-title>

              <v-spacer />
              <v-btn icon />
            </v-app-bar>

            <v-container>
              <v-row dense>
                <v-col cols="12">
                  <v-card color="#385F73" dark>
                    <v-card-title class="text-h5">
                      $29.990
                    </v-card-title>

                    <v-card-subtitle>
                      35 GB, Redes sociales Libres, Minutos Libres, App Movil MI
                      WOM, Waze, Telegram, Spotyfy, YoTube LIBRES!
                    </v-card-subtitle>

                    <v-card-actions>
                      <v-btn text>
                        Agregar
                      </v-btn>
                    </v-card-actions>
                  </v-card>
                </v-col>

                <v-col v-for="(item, i) in items" :key="i" cols="12">
                  <v-card :color="item.color" dark>
                    <div class="d-flex flex-no-wrap justify-space-between">
                      <div>
                        <v-card-title class="text-h5" v-text="item.title" />

                        <v-card-subtitle v-text="item.artist" />

                        <v-card-actions>
                          <v-btn
                            v-if="item.artist === 'Ellie Goulding'"
                            class="ml-2 mt-3"
                            fab
                            icon
                            height="40px"
                            right
                            width="40px"
                          >
                            <v-icon>mdi-play</v-icon>
                          </v-btn>

                          <v-btn
                            v-else
                            class="ml-2 mt-5"
                            outlined
                            rounded
                            small
                          >
                            START RADIO
                          </v-btn>
                        </v-card-actions>
                      </div>

                      <v-avatar class="ma-3" size="125" tile>
                        <v-img :src="item.src" />
                      </v-avatar>
                    </div>
                  </v-card>
                </v-col>
              </v-row>
            </v-container>
          </v-card>
        </v-card>
      </v-col>
      <v-col>
        <v-card
          class="pa-2"
          outlined
          tile
        >
                   <v-card max-width="400" class="mx-auto">
            <v-app-bar dark color="pink">
              <v-app-bar-nav-icon />

              <v-toolbar-title>PLAN EMPODÉRATE XXL</v-toolbar-title>

              <v-spacer />
              <v-btn icon />
            </v-app-bar>

            <v-container>
              <v-row dense>
                <v-col cols="12">
                  <v-card color="#385F73" dark>
                    <v-card-title class="text-h5">
                      $59.990
                    </v-card-title>

                    <v-card-subtitle>
                      60 GB, Redes sociales Libres, Minutos Libres, Comparte
                      GIGAS App Movil MI WOM, 500 Minuros a Canada, Puerto Rico,
                      Estados Unidos y España tambien Waze, Telegram, Spotyfy,
                      YoTube LIBRES!
                    </v-card-subtitle>

                    <v-card-actions>
                      <v-btn text>
                        Agregar
                      </v-btn>
                    </v-card-actions>
                  </v-card>
                </v-col>

                <v-col v-for="(item, i) in items" :key="i" cols="12">
                  <v-card :color="item.color" dark>
                    <div class="d-flex flex-no-wrap justify-space-between">
                      <div>
                        <v-card-title class="text-h5" v-text="item.title" />

                        <v-card-subtitle v-text="item.artist" />

                        <v-card-actions>
                          <v-btn
                            v-if="item.artist === 'Ellie Goulding'"
                            class="ml-2 mt-3"
                            fab
                            icon
                            height="40px"
                            right
                            width="40px"
                          >
                            <v-icon>mdi-play</v-icon>
                          </v-btn>

                          <v-btn
                            v-else
                            class="ml-2 mt-5"
                            outlined
                            rounded
                            small
                          >
                            START RADIO
                          </v-btn>
                        </v-card-actions>
                      </div>

                      <v-avatar class="ma-3" size="125" tile>
                        <v-img :src="item.src" />
                      </v-avatar>
                    </div>
                  </v-card>
                </v-col>
              </v-row>
            </v-container>
          </v-card>
        </v-card>
      </v-col>
      <v-col order="first">
        <v-card
          class="pa-2"
          outlined
          tile
        >
                    <v-card max-width="400" class="mx-auto">
            <v-app-bar dark color="pink">
              <v-app-bar-nav-icon />

              <v-toolbar-title>PLAN XS </v-toolbar-title>

              <v-spacer />
              <v-btn icon />
            </v-app-bar>

            <v-container>
              <v-row dense>
                <v-col cols="12">
                  <v-card color="#385F73" dark>
                    <v-card-title class="text-h5">
                      $19.990
                    </v-card-title>

                    <v-card-subtitle>
                      7 GB, Minutos Libres a todo operador
                       App Movil MI WOM, WhatsApp,Waze, Spotyfy,
                      LIBRES!
                    </v-card-subtitle>

                    <v-card-actions>
                      <v-btn text>
                        Agregar
                      </v-btn>
                    </v-card-actions>
                  </v-card>
                </v-col>

                <v-col v-for="(item, i) in items" :key="i" cols="12">
                  <v-card :color="item.color" dark>
                    <div class="d-flex flex-no-wrap justify-space-between">
                      <div>
                        <v-card-title class="text-h5" v-text="item.title" />

                        <v-card-subtitle v-text="item.artist" />

                        <v-card-actions>
                          <v-btn
                            v-if="item.artist === 'Ellie Goulding'"
                            class="ml-2 mt-3"
                            fab
                            icon
                            height="40px"
                            right
                            width="40px"
                          >
                            <v-icon>mdi-play</v-icon>
                          </v-btn>

                          <v-btn
                            v-else
                            class="ml-2 mt-5"
                            outlined
                            rounded
                            small
                          >
                            START RADIO
                          </v-btn>
                        </v-card-actions>
                      </div>

                      <v-avatar class="ma-3" size="125" tile>
                        <v-img :src="item.src" />
                      </v-avatar>
                    </div>
                  </v-card>
                </v-col>
              </v-row>
            </v-container>
          </v-card>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped></style>
