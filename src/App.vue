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
              <v-container class="grey darken-3 pt-8">
                  <v-row no-gutters>
                    <v-col
                      v-for="n in 4"
                      :key="key(n+11)"
                      cols="3"
                      align="center"
                    >
                      <v-btn x-large="" class="white--text" @click.stop="press(key(n+11))" icon>
                        {{ key(n+11) }}
                      </v-btn>
                    </v-col>
                  </v-row>
                  <v-row class="mt-2" no-gutters>
                    <v-col
                      v-for="n in 4"
                      :key="key(n+11)"
                      cols="3"
                      align="center"
                    >
                      <v-btn x-large="" class="white--text" @click.stop="press(key(n+7))" icon>
                        {{ key(n+7) }}
                      </v-btn>
                    </v-col>
                  </v-row>
                  <v-row class="mt-2" no-gutters>
                    <v-col
                      v-for="n in 4"
                      :key="key(n+11)"
                      cols="3"
                      align="center"
                    >
                      <v-btn x-large="" class="white--text" @click.stop="press(key(n+3))" icon>
                        {{ key(n+3) }}
                      </v-btn>
                    </v-col>
                  </v-row>
                  <v-row class="mt-2" no-gutters>
                    <v-col
                      v-for="n in 4"
                      :key="key(n+11)"
                      cols="3"
                      align="center"
                    >
                      <v-btn x-large="" class="white--text" @click.stop="press(key(n-1))" icon>
                        {{ key(n-1) }}
                      </v-btn>
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

  methods: {
    noop() {
      console.log('noop')
    },
    key(i) {
      if(i > 9) {
        return i.toString(16)
      }
      return i.toString()
    },
    press(key) {
      console.log(key)
    }
  },

  
};
</script>

<style lang="scss" scoped>
.over-hidden {
  overflow: hidden;
}
</style>
