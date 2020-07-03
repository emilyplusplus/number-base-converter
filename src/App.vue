<template>
  <v-app>
    <v-content>
      <v-container fill-height fluid>
        <v-row align="center" justify="center">
          <v-col>
            <v-card
              class="mx-auto"
              max-width="400"
              height="600"
            >
              <v-container class="grey lighten-5">
                <v-col cols="12" sm="6">
                  <v-text-field
                    label="Regular"
                    single-line
                  ></v-text-field>
                </v-col>
                <v-col cols="12" sm="6">
                  <v-text-field
                    label="Regular"
                    single-line
                  ></v-text-field>
                </v-col>
                <v-col cols="12" sm="6">
                  <v-text-field
                    label="Regular"
                    single-line
                  ></v-text-field>
                </v-col>
                <v-row no-gutters>
                  <v-col
                    v-for="n in 3"
                    :key="n"
                    cols="12"
                    sm="4"
                  >
                    <v-card
                      class="pa-2"
                      outlined
                      tile
                    >
                      One of three columns
                    </v-card>
                  </v-col>
                </v-row>
                <v-row no-gutters>
                  <v-col
                    v-for="n in 3"
                    :key="n"
                    cols="12"
                    sm="4"
                  >
                    <v-card
                      class="pa-2"
                      outlined
                      tile
                    >
                      One of three columns
                    </v-card>
                  </v-col>
                </v-row>
                <v-row no-gutters>
                  <v-col
                    v-for="n in 3"
                    :key="n"
                    cols="12"
                    sm="4"
                  >
                    <v-card
                      class="pa-2"
                      outlined
                      tile
                    >
                      One of three columns
                    </v-card>
                  </v-col>
                </v-row>
                <v-row no-gutters>
                  <v-col
                    v-for="n in 3"
                    :key="n"
                    cols="12"
                    sm="4"
                  >
                    <v-card
                      class="pa-2"
                      outlined
                      tile
                    >
                      One of three columns
                    </v-card>
                  </v-col>
                </v-row>
              </v-container>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: 'App',

  components: {
    
  },

  data: () => ({
    
  }),
};
</script>
