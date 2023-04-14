<template>
  <div>
    <!-- Carousel in Event App -->
    <section>
      <v-carousel show-arrows-on-hover cycle class="slide">
        <v-carousel-item
          v-for="(item, i) in items"
          :key="i"
          :src="item.src"
          reverse-transition="fade-transition"
          transition="fade-transition"
        ></v-carousel-item>
      </v-carousel>
    </section>

    <!-- Cards in UpcomingEvent App -->
    <section>
      <div class="whole">
        <div class="text"><h1>Upcoming Events</h1></div>
        <div id="app">
          <v-app id="inspire">
            <v-row>
              <!-- 1 -->
              <v-col>
                <v-card class="mx-auto" max-width="344">
                  <v-img
                    src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
                    height="200px"
                  ></v-img>

                  <v-card-title> Reverb </v-card-title>

                  <v-card-subtitle>
                    Reverb is a cultural fest of Symbiosis Institute of
                    Technology
                  </v-card-subtitle>

                  <v-card-actions>
                    <v-btn color="orange lighten-2" text> Explore </v-btn>

                    <v-spacer></v-spacer>

                    <v-btn icon @click="show1 = !show1">
                      <v-icon>{{
                        show1 ? "mdi-chevron-up" : "mdi-chevron-down"
                      }}</v-icon>
                    </v-btn>
                  </v-card-actions>

                  <v-expand-transition>
                    <div v-show="show1">
                      <v-divider></v-divider>

                      <v-card-text>
                        I'm a thing. But, like most politicians, he promised
                        more than he could deliver. You won't have time for
                        sleeping, soldier, not with all the bed making you'll be
                        doing. Then wre'll go with that data file! Hey, you add a
                        one and two zeros to that or we walk! You're going to do
                        his laundry? I've got to find a way to escape.
                      </v-card-text>
                    </div>
                  </v-expand-transition>
                </v-card>
              </v-col>

              <!-- 2 -->
              <v-col>
                <v-card class="mx-auto" max-width="344">
                  <v-img
                    src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
                    height="200px"
                  ></v-img>

                  <v-card-title> Reverb </v-card-title>

                  <v-card-subtitle>
                    Reverb is a cultural fest of Symbiosis Institute of
                    Technology
                  </v-card-subtitle>

                  <v-card-actions>
                    <v-btn color="orange lighten-2" text> Explore </v-btn>

                    <v-spacer></v-spacer>

                    <v-btn icon @click="show2 = !show2">
                      <v-icon>{{
                        show2 ? "mdi-chevron-up" : "mdi-chevron-down"
                      }}</v-icon>
                    </v-btn>
                  </v-card-actions>

                  <v-expand-transition>
                    <div v-show="show2">
                      <v-divider></v-divider>

                      <v-card-text>
                        I'm a thing. But, like most politicians, he promised
                        more than he could deliver. You won't have time for
                        sleeping, soldier, not with all the bed making you'll be
                        doing. Then we'll go with that data file! Hey, you add a
                        one and two zeros to that or we walk! You're going to do
                        his laundry? I've got to find a way to escape.
                      </v-card-text>
                    </div>
                  </v-expand-transition>
                </v-card>
              </v-col>
              <!-- 3 -->
              <v-col>
                <v-card class="mx-auto" max-width="344">
                  <v-img
                    src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
                    height="200px"
                  ></v-img>

                  <v-card-title> Reverb </v-card-title>

                  <v-card-subtitle>
                    Reverb is a cultural fest of Symbiosis Institute of
                    Technology
                  </v-card-subtitle>

                  <v-card-actions>
                    <v-btn color="orange lighten-2" text> Explore </v-btn>

                    <v-spacer></v-spacer>

                    <v-btn icon @click="show3 = !show3">
                      <v-icon>{{
                        show3 ? "mdi-chevron-up" : "mdi-chevron-down"
                      }}</v-icon>
                    </v-btn>
                  </v-card-actions>

                  <v-expand-transition>
                    <div v-show="show3">
                      <v-divider></v-divider>

                      <v-card-text>
                        I'm a thing. But, like most politicians, he promised
                        more than he could deliver. You won't have time for
                        sleeping, soldier, not with all the bed making you'll be
                        doing. Then we'll go with that data file! Hey, you add a
                        one and two zeros to that or we walk! You're going to do
                        his laundry? I've got to find a way to escape.
                      </v-card-text>
                    </div>
                  </v-expand-transition>
                </v-card>
              </v-col>
            </v-row>
            <v-row>
              <!-- 4 -->
              <v-col>
                <v-card class="mx-auto" max-width="344">
                  <v-img
                    src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
                    height="200px"
                  ></v-img>

                  <v-card-title> Reverb </v-card-title>

                  <v-card-subtitle>
                    Reverb is a cultural fest of Symbiosis Institute of
                    Technology
                  </v-card-subtitle>

                  <v-card-actions>
                    <v-btn color="orange lighten-2" text> Explore </v-btn>

                    <v-spacer></v-spacer>

                    <v-btn icon @click="show4 = !show4">
                      <v-icon>{{
                        show4 ? "mdi-chevron-up" : "mdi-chevron-down"
                      }}</v-icon>
                    </v-btn>
                  </v-card-actions>

                  <v-expand-transition>
                    <div v-show="show4">
                      <v-divider></v-divider>

                      <v-card-text>
                        I'm a thing. But, like most politicians, he promised
                        more than he could deliver. You won't have time for
                        sleeping, soldier, not with all the bed making you'll be
                        doing. Then we'll go with that data file! Hey, you add a
                        one and two zeros to that or we walk! You're going to do
                        his laundry? I've got to find a way to escape.
                      </v-card-text>
                    </div>
                  </v-expand-transition>
                </v-card>
              </v-col>
              <!-- 5 -->
              <v-col>
                <v-card class="mx-auto" max-width="344">
                  <v-img
                    src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
                    height="200px"
                  ></v-img>

                  <v-card-title> Reverb </v-card-title>

                  <v-card-subtitle>
                    Reverb is a cultural fest of Symbiosis Institute of
                    Technology
                  </v-card-subtitle>

                  <v-card-actions>
                    <v-btn color="orange lighten-2" text> Explore </v-btn>

                    <v-spacer></v-spacer>

                    <v-btn icon @click="show5 = !show5">
                      <v-icon>{{
                        show5 ? "mdi-chevron-up" : "mdi-chevron-down"
                      }}</v-icon>
                    </v-btn>
                  </v-card-actions>

                  <v-expand-transition>
                    <div v-show="show5">
                      <v-divider></v-divider>

                      <v-card-text>
                        I'm a thing. But, like most politicians, he promised
                        more than he could deliver. You won't have time for
                        sleeping, soldier, not with all the bed making you'll be
                        doing. Then we'll go with that data file! Hey, you add a
                        one and two zeros to that or we walk! You're going to do
                        his laundry? I've got to find a way to escape.
                      </v-card-text>
                    </div>
                  </v-expand-transition>
                </v-card>
              </v-col>
              <!-- 6 -->
              <v-col>
                <v-card class="mx-auto" max-width="344">
                  <v-img
                    src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
                    height="200px"
                  ></v-img>

                  <v-card-title> Reverb </v-card-title>

                  <v-card-subtitle>
                    Reverb is a cultural fest of Symbiosis Institute of
                    Technology
                  </v-card-subtitle>

                  <v-card-actions>
                    <v-btn color="orange lighten-2" text> Explore </v-btn>

                    <v-spacer></v-spacer>

                    <v-btn icon @click="show6 = !show6">
                      <v-icon>{{
                        show6 ? "mdi-chevron-up" : "mdi-chevron-down"
                      }}</v-icon>
                    </v-btn>
                  </v-card-actions>

                  <v-expand-transition>
                    <div v-show="show6">
                      <v-divider></v-divider>

                      <v-card-text>
                        I'm a thing. But, like most politicians, he promised
                        more than he could deliver. You won't have time for
                        sleeping, soldier, not with all the bed making you'll be
                        doing. Then we'll go with that data file! Hey, you add a
                        one and two zeros to that or we walk! You're going to do
                        his laundry? I've got to find a way to escape.
                      </v-card-text>
                    </div>
                  </v-expand-transition>
                </v-card>
              </v-col>
            </v-row>
          </v-app>
        </div>
      </div>
    </section>
    <!-- Cards of PastEvent App -->

    <section>
      <div class="whole">
        <div class="text"><h1>Past Events</h1></div>
        <div id="app">
          <v-app id="inspire">
            <!-- 1 -->
            <v-row>
              <v-col>
                <v-card class="mx-auto" max-width="400">
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                  >
                    <v-card-title>Top 10 Australian beaches</v-card-title>
                  </v-img>

                  <v-card-subtitle class="pb-0"> Number 10 </v-card-subtitle>

                  <v-card-text class="text--primary">
                    <div>Whitehaven Beach</div>

                    <div>Whitsunday Island, Whitsunday Islands</div>
                  </v-card-text>

                  <v-card-actions>
                    <v-btn color="orange" text> Share </v-btn>

                    <v-btn color="orange" text> Explore </v-btn>
                  </v-card-actions>
                </v-card>
              </v-col>
              <v-col>
                <!-- 2 -->
                <v-card class="mx-auto" max-width="400">
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                  >
                    <v-card-title>Top 10 Australian beaches</v-card-title>
                  </v-img>

                  <v-card-subtitle class="pb-0"> Number 10 </v-card-subtitle>

                  <v-card-text class="text--primary">
                    <div>Whitehaven Beach</div>

                    <div>Whitsunday Island, Whitsunday Islands</div>
                  </v-card-text>

                  <v-card-actions>
                    <v-btn color="orange" text> Share </v-btn>

                    <v-btn color="orange" text> Explore </v-btn>
                  </v-card-actions>
                </v-card>
              </v-col>
              <!-- 3 -->
              <v-col>
                <v-card class="mx-auto" max-width="400">
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                  >
                    <v-card-title>Top 10 Australian beaches</v-card-title>
                  </v-img>

                  <v-card-subtitle class="pb-0"> Number 10 </v-card-subtitle>

                  <v-card-text class="text--primary">
                    <div>Whitehaven Beach</div>

                    <div>Whitsunday Island, Whitsunday Islands</div>
                  </v-card-text>

                  <v-card-actions>
                    <v-btn color="orange" text> Share </v-btn>

                    <v-btn color="orange" text> Explore </v-btn>
                  </v-card-actions>
                </v-card>
              </v-col>
            </v-row>
            <!-- 4 -->

            <v-row>
              <v-col>
                <v-card class="mx-auto" max-width="400">
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                  >
                    <v-card-title>Top 10 Australian beaches</v-card-title>
                  </v-img>

                  <v-card-subtitle class="pb-0"> Number 10 </v-card-subtitle>

                  <v-card-text class="text--primary">
                    <div>Whitehaven Beach</div>

                    <div>Whitsunday Island, Whitsunday Islands</div>
                  </v-card-text>

                  <v-card-actions>
                    <v-btn color="orange" text> Share </v-btn>

                    <v-btn color="orange" text> Explore </v-btn>
                  </v-card-actions>
                </v-card>
              </v-col>
              <!-- 5 -->
              <v-col>
                <v-card class="mx-auto" max-width="400">
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                  >
                    <v-card-title>Top 10 Australian beaches</v-card-title>
                  </v-img>

                  <v-card-subtitle class="pb-0"> Number 10 </v-card-subtitle>

                  <v-card-text class="text--primary">
                    <div>Whitehaven Beach</div>

                    <div>Whitsunday Island, Whitsunday Islands</div>
                  </v-card-text>

                  <v-card-actions>
                    <v-btn color="orange" text> Share </v-btn>

                    <v-btn color="orange" text> Explore </v-btn>
                  </v-card-actions>
                </v-card>
              </v-col>
              <!-- 6 -->
              <v-col>
                <v-card class="mx-auto" max-width="400">
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                  >
                    <v-card-title>Top 10 Australian beaches</v-card-title>
                  </v-img>

                  <v-card-subtitle class="pb-0"> Number 10 </v-card-subtitle>

                  <v-card-text class="text--primary">
                    <div>Whitehaven Beach</div>

                    <div>Whitsunday Island, Whitsunday Islands</div>
                  </v-card-text>

                  <v-card-actions>
                    <v-btn color="orange" text> Share </v-btn>

                    <v-btn color="orange" text> Explore </v-btn>
                  </v-card-actions>
                </v-card>
              </v-col>
              <!-- 7 -->
              <v-col>
                <v-card class="mx-auto" max-width="400">
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                  >
                    <v-card-title>Top 10 Australian beaches</v-card-title>
                  </v-img>

                  <v-card-subtitle class="pb-0"> Number 10 </v-card-subtitle>

                  <v-card-text class="text--primary">
                    <div>Whitehaven Beach</div>

                    <div>Whitsunday Island, Whitsunday Islands</div>
                  </v-card-text>

                  <v-card-actions>
                    <v-btn color="orange" text> Share </v-btn>

                    <v-btn color="orange" text> Explore </v-btn>
                  </v-card-actions>
                </v-card>
              </v-col>
              <!-- 8 -->
              <v-col>
                <v-card class="mx-auto" max-width="400">
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                  >
                    <v-card-title>Top 10 Australian beaches</v-card-title>
                  </v-img>

                  <v-card-subtitle class="pb-0"> Number 10 </v-card-subtitle>

                  <v-card-text class="text--primary">
                    <div>Whitehaven Beach</div>

                    <div>Whitsunday Island, Whitsunday Islands</div>
                  </v-card-text>

                  <v-card-actions>
                    <v-btn color="orange" text> Share </v-btn>

                    <v-btn color="orange" text> Explore </v-btn>
                  </v-card-actions>
                </v-card>
              </v-col>
            </v-row>
          </v-app>
        </div>
      </div>
    </section>
    <section>
      <div class="foot">
        <div id="app">
          <v-app id="inspire">
            <v-footer dark padless>
              <v-card
                flat
                tile
                class="indigo lighten-1 white--text text-center"
              >
                <v-card-text>
                  <v-btn
                    v-for="icon in icons"
                    :key="icon"
                    class="mx-4 white--text"
                    icon
                  >
                    <v-icon size="24px">
                      {{ icon }}
                    </v-icon>
                  </v-btn>
                </v-card-text>

                <v-card-text class="white--text pt-0">
                  Phasellus feugiat arcu sapien, et iaculis ipsum elementum sit
                  amet. Mauris cursus commodo interdum. Praesent ut risus eget
                  metus luctus accumsan id ultrices nunc. Sed at orci sed massa
                  consectetur dignissim a sit amet dui. Duis commodo vitae velit
                  et faucibus. Morbi vehicula lacinia malesuada. Nulla placerat
                  augue vel ipsum ultrices, cursus iaculis dui sollicitudin.
                  Vestibulum eu ipsum vel diam elementum tempor vel ut orci.
                  Orci varius natoque penatibus et magnis dis parturient montes,
                  nascetur ridiculus mus.
                </v-card-text>

                <v-divider></v-divider>

                <v-card-text class="white--text">
                  {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
                </v-card-text>
              </v-card>
            </v-footer>
          </v-app>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {
      show1: false,
      show2: false,
      show3: false,
      show4: false,
      show5: false,
      show6: false,
      icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
      items: [
        {
          src: "https://cdn.vuetifyjs.com/images/carousel/squirrel.jpg",
        },
        {
          src: "https://cdn.vuetifyjs.com/images/carousel/sky.jpg",
        },
        {
          src: "https://cdn.vuetifyjs.com/images/carousel/bird.jpg",
        },
        {
          src: "https://cdn.vuetifyjs.com/images/carousel/planet.jpg",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
.row {
  display: flex;
  flex-wrap: wrap;
  flex: 1 1 auto;
  margin: -5px;
  position: relative;
  left: 9px;
}
.text {
  position: relative;
  left: 42%;
  font-size: 22px;
  margin-bottom: 20px;
  margin-top: 19px;
}
.whole {
  background-color: antiquewhite;
}
.foot {
    margin-top: 76px;
}
</style>