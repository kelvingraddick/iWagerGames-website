<template>
  <div>

    <!-- Hero section -->
    <div class="relative bg-gray-900 overflow-hidden">
      <main class="mt-8 sm:mt-16 md:mt-20 lg:mt-24 sm:mb-16 md:mb-20 lg:mb-24">
        <div class="mx-auto max-w-screen-xl">
          <div class="lg:grid lg:grid-cols-12 lg:gap-8">
            <div class="px-4 sm:px-6 sm:text-center md:max-w-2xl md:mx-auto lg:col-span-6 lg:text-left lg:flex lg:items-center">
              <div>
                <h2 class="mt-4 text-4xl tracking-tight leading-10 font-extrabold text-white sm:mt-5 sm:leading-none sm:text-6xl lg:mt-6 lg:text-5xl xl:text-6xl">
                  iWagerGames!
                  <br class="hidden md:inline">
                  <span class="text-red-500">Coming soon!</span>
                </h2>
                <p class="mt-3 text-base text-gray-300 sm:mt-5 sm:text-xl lg:text-lg xl:text-xl">
                  Compete and wager for real money playing <b>videos games</b> againts others across the glode on the <span class="text-yellow-200">iWagerGames</span> platform
                </p>
                <p class="mt-8 text-sm text-white uppercase tracking-wide font-semibold sm:mt-10">On your favorite platforms:</p>
                <div class="mt-5 w-full sm:mx-auto sm:max-w-lg lg:ml-0">
                  <div class="flex flex-wrap items-start justify-between">
                    <div class="flex justify-center px-1">
                      <img class="platform-logos h-10 sm:h-11" src="/playstation.png" alt="Playstation">
                    </div>
                    <div class="flex justify-center px-1">
                      <img class="platform-logos h-9 sm:h-10" src="/xbox.png" alt="Xbox">
                    </div>
                    <div class="flex justify-center px-1">
                      <img class="platform-logos h-8 sm:h-9" src="/windows.png" alt="Windows">
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </main>
    </div>

    <!-- How does it work? -->
    <div class="py-16 bg-gray-50 overflow-hidden lg:py-24">
      <div class="relative max-w-xl mx-auto px-4 lg:max-w-screen-xl">
        <svg class="hidden lg:block absolute left-full transform -translate-x-1/2 -translate-y-1/4" width="404" height="784" fill="none" viewBox="0 0 404 784">
          <defs>
            <pattern id="b1e6e422-73f8-40a6-b5d9-c8586e37e0e7" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
              <rect x="0" y="0" width="4" height="4" class="text-gray-200" fill="currentColor" />
            </pattern>
          </defs>
          <rect width="404" height="784" fill="url(#b1e6e422-73f8-40a6-b5d9-c8586e37e0e7)" />
        </svg>

        <div class="relative lg:grid lg:grid-cols-2 lg:gap-8 lg:items-center">
          <div class="relative">
            <h4 class="text-3xl leading-8 font-extrabold text-gray-900 tracking-tight sm:text-4xl sm:leading-9">
              How will it work?
            </h4>
            <p class="mt-3 text-xl leading-7 text-gray-500">
              Competing for money on iWagerGames is easy. Follow the steps below:
            </p>

            <ul class="mt-10">
              <li>
                <div class="flex">
                  <div class="flex-shrink-0">
                    <div class="flex items-center justify-center h-12 w-12 rounded-md bg-yellow-200 text-gray-900">
                      <!-- Heroicon name: globe-alt -->
                      <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 16l2.879-2.879m0 0a3 3 0 104.243-4.242 3 3 0 00-4.243 4.242zM21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                      </svg>
                      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 16l2.879-2.879m0 0a3 3 0 104.243-4.242 3 3 0 00-4.243 4.242zM21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                      </svg>
                    </div>
                  </div>
                  <div class="ml-4">
                    <h5 class="text-lg leading-6 font-medium text-gray-900">Choose a game / Choose a platform</h5>
                    <p class="mt-2 text-base leading-6 text-gray-500">
                      Choose from our group of select games and platforms. We are continuously working to add more games every day!
                    </p>
                  </div>
                </div>
              </li>
              <li class="mt-10">
                <div class="flex">
                  <div class="flex-shrink-0">
                    <div class="flex items-center justify-center h-12 w-12 rounded-md bg-yellow-200 text-gray-900">
                      <!-- Heroicon name: scale -->
                      <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 12h14M5 12a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v4a2 2 0 01-2 2M5 12a2 2 0 00-2 2v4a2 2 0 002 2h14a2 2 0 002-2v-4a2 2 0 00-2-2m-2-4h.01M17 16h.01" />
                      </svg>
                    </div>
                  </div>
                  <div class="ml-4">
                    <h5 class="text-lg leading-6 font-medium text-gray-900">Find a match</h5>
                    <p class="mt-2 text-base leading-6 text-gray-500">
                      Let our matchmaking system pair you with a competitor of similar history and skill.
                    </p>
                  </div>
                </div>
              </li>
              <li class="mt-10">
                <div class="flex">
                  <div class="flex-shrink-0">
                    <div class="flex items-center justify-center h-12 w-12 rounded-md bg-yellow-200 text-gray-900">
                      <!-- Heroicon name: lightning-bolt -->
                      <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 9V7a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2m2 4h10a2 2 0 002-2v-6a2 2 0 00-2-2H9a2 2 0 00-2 2v6a2 2 0 002 2zm7-5a2 2 0 11-4 0 2 2 0 014 0z" />
                      </svg>
                    </div>
                  </div>
                  <div class="ml-4">
                    <h5 class="text-lg leading-6 font-medium text-gray-900">Compete and win</h5>
                    <p class="mt-2 text-base leading-6 text-gray-500">
                      Start your game and compete. Afterwards report the result here to recieve your reward when you win.
                    </p>
                  </div>
                </div>
              </li>
            </ul>
          </div>

          <div class="mt-10 -mx-4 relative lg:mt-0">
            <svg class="absolute left-1/2 transform -translate-x-1/2 translate-y-16 lg:hidden" width="784" height="404" fill="none" viewBox="0 0 784 404">
              <defs>
                <pattern id="ca9667ae-9f92-4be7-abcb-9e3d727f2941" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
                  <rect x="0" y="0" width="4" height="4" class="text-gray-200" fill="currentColor" />
                </pattern>
              </defs>
              <rect width="784" height="404" fill="url(#ca9667ae-9f92-4be7-abcb-9e3d727f2941)" />
            </svg>
            <img class="relative mx-auto rounded-lg" width="490" src="/esports-1.png" alt="">
          </div>
        </div>

      </div>
    </div>

    <!-- Games section -->
    <div class="relative bg-gray-50 pt-16 pb-20 px-4 sm:px-6 lg:pt-24 lg:pb-28 lg:px-8">
      <div class="absolute inset-0">
        <div class="bg-white h-1/3 sm:h-2/3"></div>
      </div>
      <div class="relative max-w-7xl mx-auto">
        <div class="text-center">
          <h2 class="text-3xl leading-9 tracking-tight font-extrabold text-gray-900 sm:text-4xl sm:leading-10">
            Future games
          </h2>
          <p class="mt-3 max-w-2xl mx-auto text-xl leading-7 text-gray-500 sm:mt-4">
            When iWagerGames launches you'll be able to join one of our game rooms!
          </p>
        </div>
        <div class="mt-12 grid gap-5 max-w-lg mx-auto lg:grid-cols-3 lg:max-w-none">
          <div v-for="game in games" :key="game._id" class="flex flex-col rounded-lg shadow-lg overflow-hidden">
            <div class="flex-shrink-0">
              <img class="h-48 w-full object-cover" :src="game.bannerImageUrl" alt="">
            </div>
            <div class="flex-1 bg-white p-6 flex flex-col justify-between">
              <div class="flex-1">
                <p class="text-sm leading-5 font-medium text-indigo-600">
                  <template v-for="(platformId, index) in game.platforms">
                    <template v-if="index > 0"> | </template>
                    <a href="#" class="hover:underline" :key="platformId">
                      {{ getPlatformName(platformId) }}
                    </a>
                  </template>
                </p>
                <a href="#" class="block">
                  <h3 class="mt-2 text-xl leading-7 font-semibold text-gray-900">
                    {{ game.name }}
                  </h3>
                  <p class="mt-3 text-base leading-6 text-gray-500">
                    {{ game.description }}
                  </p>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- CTA -->
    <div class="bg-gray-900">
      <div class="max-w-2xl mx-auto text-center py-16 px-4 sm:py-20 sm:px-6 lg:px-8">
        <h2 class="text-3xl leading-9 font-extrabold text-white sm:text-4xl sm:leading-10">
          <span class="block">iWagerGames</span>
          <span class="block text-red-500">Coming soon!</span>
        </h2>
      </div>
    </div>

  </div>
</template>

<script>
import Platforms from '@/constants/platforms.js';

export default {
  layout: 'splash',
  components: {
  },
  data: function() {
    return {
      games: null
    }
  },
  async asyncData({ params }) {
    return fetch('https://api.iwagergames.com/games/', { method: 'GET' })
      .then((response) => { 
        if (response.status == 200) {
          return response.json()
          .then((responseJson) => {
            if (responseJson.isSuccess) {
              return { games: responseJson.games };
            }
          })
        }
        return undefined;
      })
      .catch((error) => {
        console.error(error);
        return undefined;
      });
  },
  methods: {
    getPlatformName(id) {
      return Platforms[id];
    }
  }
}
</script>

<style>
  .platform-logos {
    filter: grayscale(100%);
  }
</style>