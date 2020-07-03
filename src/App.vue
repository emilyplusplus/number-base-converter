<template>
  <v-app>
    <v-main>
      <v-container fill-height fluid>
        <v-row align="center" justify="center">
          <v-col>
            <v-card
              class="mx-auto over-hidden grey darken-3"
              max-width="400"
              height="700"
              elevation="12"
            >
              <v-container class="white">
                <v-row no-gutters>
                  <v-col cols="12">
                    <div style="height: 225px;"></div>
                  </v-col>
                </v-row>
                <v-row no-gutters>
                  <v-col cols="12">
                    
                  </v-col>
                </v-row>
                <v-row no-gutters>
                  <v-col cols="12">
                    
                  </v-col>
                </v-row>
                <v-row no-gutters>
                  <v-col cols="12">
                    
                  </v-col>
                </v-row>
              </v-container>
              <v-container class="grey darken-3">
                  <v-row no-gutters>
                    <v-col
                      v-for="n in 4"
                      :key="n"
                      cols="3"
                    >
                      <v-button @click.stop icon>
                        A
                      </v-button>
                    </v-col>
                  </v-row>
                  <v-row no-gutters>
                    <v-col
                      v-for="n in 4"
                      :key="n"
                      cols="3"
                    >
                      <v-button icon>
                        7
                      </v-button>
                    </v-col>
                  </v-row>
                  <v-row no-gutters>
                    <v-col
                      v-for="n in 4"
                      :key="n"
                      cols="3"
                    >
                      <v-button icon>
                        4
                      </v-button>
                    </v-col>
                  </v-row>
                  <v-row no-gutters>
                    <v-col
                      v-for="n in 4"
                      :key="n"
                      cols="3"
                    >
                      <v-button icon>
                        0
                      </v-button>
                    </v-col>
                  </v-row>
                </v-container>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
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

<style lang="scss" scoped>
.over-hidden {
  overflow: hidden;
}
</style>
