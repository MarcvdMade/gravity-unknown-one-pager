<template>
    <div>
        <v-parallax
        class="height-vh"
          src="../../public/img/game.png"
          height="100vh"
        >
          <v-row
            align="center"
            justify="center"
          >
            <v-col
              class="text-center"
              cols="12"
            >
              <h1 class="text-6xl font-bold mb-4 text-black">
                Gravity: Unknown
              </h1>
              <h4 class="text-2xl text-black">
                Gravity bending gameplay
              </h4>
            </v-col>
          </v-row>
        </v-parallax>
        
        <div>
            <p class="text-7xl text-center mt-20 font-bold">What do I want to learn?</p>
            <p class="text-5xl text-center mt-10 line-through">Web Development</p>
            <p class="text-5xl text-center mt-10">🔽🔽🔽</p>
            <p class="text-5xl text-center mt-10">Game Development</p>
        </div>

        <div class="mt-36">
            <p class="text-6xl text-center font-bold mb-10">Roadmap</p>
            <img class="w-5/6 mx-auto rounded-xl" src="../../public/img/roadmap.png" />
            <div class="mx-auto text-center">
                <a href="https://trello.com/b/S8vOTfic/gravity-unknown-roadmap">
                    <button class="mx-auto mt-10 border-solid border-4 border-blue-500 hover:bg-blue-500 transition-all duration-150 rounded-xl px-8 py-4 text-blue-500 hover:text-white font-bold text-4xl uppercase">To Trello 🦸‍♂️</button>
                </a>
            </div>
        </div>

        <div class="mt-36 pb-20 bg-blue-300">
            <p class="text-6xl text-center font-bold pt-10 mb-10 text-white">Research</p>
            <v-card
                class="mx-auto w-2/4 text-center"
                tile
              >
                <v-list-item>
                  <v-list-item-content>
                    <v-list-item-title class="text-4xl">DONE</v-list-item-title>
                    <v-list-item-subtitle class="text-2xl">Unity Programming</v-list-item-subtitle>
                    <v-list-item-subtitle class="text-2xl">Game Theories</v-list-item-subtitle>
                    <v-list-item-subtitle class="text-2xl">Other Games</v-list-item-subtitle>
                    <v-list-item-subtitle class="text-2xl">Mindmap</v-list-item-subtitle>
                  </v-list-item-content>
                </v-list-item>

                <v-list-item two-line>
                  <v-list-item-content>
                    <v-list-item-title class="text-4xl">TO DO</v-list-item-title>
                    <v-list-item-subtitle class="text-2xl">Game Design</v-list-item-subtitle>
                    <v-list-item-subtitle class="text-2xl">Animations</v-list-item-subtitle>
                    <v-list-item-subtitle class="text-2xl">Level Design</v-list-item-subtitle>
                    <v-list-item-subtitle class="text-2xl">Model Design</v-list-item-subtitle>
                  </v-list-item-content>
                </v-list-item>
                <v-progress-linear
                    color="blue"
                    rounded
                    value="50"
                    height="20"
                ></v-progress-linear>
            </v-card>

            <p class="text-6xl text-center font-bold mt-20 mb-10 text-white">Mindmap</p>
            <iframe class="mx-auto" style="border:none" width="80%" height="450" src="https://whimsical.com/embed/W67NTtUoS4JgNJfVAAXYHx"></iframe>
        </div>

        <div class="mt-20">
            <img class="w-2/4 mx-auto rounded-xl" src="../../public/img/cool.gif" />
            <p class="text-6xl text-center font-bold mt-20 mb-10 text-black">Possible Struggles</p>
            <p class="text-4xl text-center font-bold mt-2 text-gray-500">Gravity function</p>
            <p class="text-4xl text-center font-bold mt-2 text-gray-500">Open world?</p>
            <p class="text-4xl text-center font-bold mt-2 text-gray-500">Fun factor?</p>
        </div>

        <div class="mt-36">
            <p class="text-6xl text-center font-bold mb-10 text-black">Sales Pitch Focus Points</p>
            <div class="flex flex-col md:flex-row flex-wrap justify-center gap-5">
              <v-card
                class="px-10 py-5 w-96 mx-auto"
                elevation="6"
                outlined
                shaped
              >
                <p class="text-4xl font-bold text-center underline">Sell your concept!</p>
                <p class="text-lg">
                  Focus more on selling the game and it's features. Don't focus to much on progress and research.
                  Talk about what makes the game amazing and why people want to play it.
                  Focus on the player changing gravity. The main focus of your game.
                </p>
              </v-card>
              <v-card
                class="px-10 py-5 w-96 mx-auto"
                elevation="6"
                outlined
                shaped
              >
                <p class="text-4xl font-bold text-center underline">Concept sketches!</p>
                <p class="text-lg">
                  Show your concept sketches. This will help with explaining your game features.
                  Make some sketches (does not matter how bad they are) and don't forget them this time.
                  Trying to explain the gravity change feature is very difficult without sketches.
                </p>
              </v-card>
              <v-card
                class="px-10 py-5 w-96 mx-auto"
                elevation="6"
                outlined
                shaped
              >
                <p class="text-4xl font-bold text-center underline">Talk about why your target audience wants to play the game!</p>
                <p class="text-lg">
                  Target audience is important. They are the people how are gonna notice your game and want to play it.
                  Talk about everything that will sell the game to them. Almost the same as the first point. If your target audience is not
                  interested nobody is gonna be interested.
                </p>
              </v-card>
            </div>
        </div>

        <p class="text-6xl text-center font-bold mt-20 text-black">Release Line</p>
        <div class="border-solid border-t-4 border-b-4 border-blue-500">
            <v-timeline>
                <v-timeline-item>BETA Release 1.0</v-timeline-item>
                <v-timeline-item class="text-right">
                    BETA Release 2.0
                </v-timeline-item>
                <v-timeline-item>BETA Release 3.0</v-timeline-item>
            </v-timeline>
        </div>

        <div class="w-2/4 mx-auto">
            <p class="text-6xl text-center font-bold mt-20 text-black">See you at the first BETA release 😉</p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Home',
    data () {
        return {

        }
    },
}
</script>

<style scoped>
    .height-vh {
        height: 100vh !important;
    }
</style>