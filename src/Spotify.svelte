<script>
  export let x;
</script>

<style>
  a {
    color: white;
    text-decoration: none;
  }
</style>

<div class="flex flex-col h-screen text-sm text-gray-400">
  <div class="flex-1 flex overflow-y-hidden">
    {x}
    <div
      class="sidebar bg-gray-800 w-48 flex-none flex flex-col justify-between
        font-semibold">
      <ul>
        <li class="border-l-4 border-green-600">
          <a href="#." class="flex items-center mx-4 mt-4">
            <svg
              class="fill-current-white"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg">
              <path
                d="M3 12L5 10M5 10L12 3L19 10M5 10V20C5 20.5523 5.44772 21 6 21H9M19 10L21 12M19 10V20C19 20.5523 18.5523 21 18 21H15M9 21C9.55228 21 10 20.5523 10 20V16C10 15.4477 10.4477 15 11 15H13C13.5523 15 14 15.4477 14 16V20C14 20.5523 14.4477 21 15 21M9 21H15"
                stroke="#4A5568"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round" />
            </svg>
            <span class="ml-2 text-white">Home</span>
          </a>
        </li>
      </ul>
      <ul>
        <li class="border-l-4 text-white border-green-600">
          <a href="#." class="flex items-center mx-4">
            <svg
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg">
              <path
                d="M19 11H5M19 11C20.1046 11 21 11.8954 21 13V19C21 20.1046 20.1046 21 19 21H5C3.89543 21 3 20.1046 3 19V13C3 11.8954 3.89543 11 5 11M19 11V9C19 7.89543 18.1046 7 17 7M5 11V9C5 7.89543 5.89543 7 7 7M7 7V5C7 3.89543 7.89543 3 9 3H15C16.1046 3 17 3.89543 17 5V7M7 7H17"
                stroke="#4A5568"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round" />
            </svg>
            <span class="ml-2 text-white">Browse</span>
          </a>
        </li>
      </ul>
      <ul>
        <li class="border-l-4 text-white border-green-600">
          <a href="#." class="flex items-center mx-4">
            <svg
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg">
              <path
                d="M5.63604 18.3639C2.12132 14.8492 2.12132 9.15071 5.63604 5.63599M18.364 5.63599C21.8787 9.15071 21.8787 14.8492 18.364 18.3639M8.46447 15.5355C6.51184 13.5829 6.51184 10.417 8.46447 8.46441M15.5355 8.46441C17.4882 10.417 17.4882 13.5829 15.5355 15.5355M13 11.9999C13 12.5522 12.5523 12.9999 12 12.9999C11.4477 12.9999 11 12.5522 11 11.9999C11 11.4477 11.4477 10.9999 12 10.9999C12.5523 10.9999 13 11.4477 13 11.9999Z"
                stroke="#374151"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round" />
            </svg>
            <span class="ml-2 text-white">Radio</span>
          </a>
        </li>
      </ul>
      <div class="overflow-y-auto px-5 mt-2">
        <h3 class="uppercase tracking-widest text-white font-semibold">
          YOUR LIBRARY
        </h3>
        <ul class="leading-loose">
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Made For You</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Recently Played</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Liked Songs</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Albums</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Artists</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Podcasts</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Made For You</a>
          </li>
        </ul>
        <h3 class="uppercase tracking-widest text-white font-semibold">
          PLAYLISTS
        </h3>
        <ul class="leading-loose">
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Acoustic Hits</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">R&B</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Pop</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Rock</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Folk and Acoustic</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Metal</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Jazz</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Hip-Hop Central</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">TGIF</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">K-Pop</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">BTS</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Pop Punk Powerhouse</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Indie Rock Road Trip</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Hip-Hop drive</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Today's Top List</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Acoustic Covers</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Discover Weekly</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">R&B Right Now</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Hot Hits India</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Top Hits India</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Trending in India</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Heavy Metal</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Today's Top Hits</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">Are & Be</a>
          </li>
          <li class="truncate">
            <a href="#." class="hover:text-green-600">iTunes</a>
          </li>
        </ul>
      </div>
      <div
        class="border-t border-gray-800 h-16 px-4 py-2 flex items-center group">
        <svg
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          xmlns="http://www.w3.org/2000/svg">
          <path
            d="M12 9V12M12 12V15M12 12H15M12 12H9M21 12C21 16.9706 16.9706 21 12 21C7.02944 21 3 16.9706 3 12C3 7.02944 7.02944 3 12 3C16.9706 3 21 7.02944 21 12Z"
            stroke="#4A5568"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round" />
        </svg>
        <a
          href="#."
          class="font-normal text-gray-500 mt-2 align-text-baseline
            hover:text-green-600">
          New Playist</a>
      </div>
    </div>

    <div class="content-area bg-gray-900 flex-1 flex flex-col">
      <div class="top-bar flex items-center justify-between px-4 py-2 mt-6">
        <div class="flex items-center">
          <button class="h-8 w-8 border-gray-900"><svg
              viewBox="0 0 24 24"
              width="12"
              height="12"
              class="fill-current text-gray-400 hover:text-green-600 h-10 w-10"><path
                d="M14.7 15.3a1 1 0 01-1.4 1.4l-4-4a1 1 0 010-1.4l4-4a1 1 0 011.4 1.4L11.42 12l3.3 3.3z" /></svg></button>
          <button class="ml-1 h-8 w-8 border-gray-900"><svg
              viewBox="0 0 24 24"
              width="24"
              height="24"
              class="fill-current text-gray-400 hover:text-green-600 h-10 w-10"><path
                d="M9.3 8.7a1 1 0 011.4-1.4l4 4a1 1 0 010 1.4l-4 4a1 1 0 01-1.4-1.4l3.29-3.3-3.3-3.3z"
                class="heroicon-ui" /></svg></button>
          <div class="ml-4 relative">
            <input
              type="text"
              placeholder="Search"
              class="h-8 w-32 bg-white text-gray-700 placeholder-gray-800
                rounded-full px-3 py-1 pl-8" />
            <div class="absolute top-0 mt-1">
              <svg
                viewBox="0 0 24 24"
                width="24"
                height="24"
                class="fill-current text-gray-800 h-6 w-6 pt-1 pl-2"><path
                  d="M16.32 14.9l5.39 5.4a1 1 0 01-1.42 1.4l-5.38-5.38a8 8 0 111.41-1.41zM10 16a6 6 0 100-12 6 6 0 000 12z"
                  class="heroicon-ui" /></svg>
            </div>
          </div>
        </div>
        <div class="flex items-center">
          <button class="border-gray-900"><svg
              viewBox="0 0 496 512"
              class="fill-current text-gray-400 hover:text-green-600 w-6 h-6"><path
                d="M248 104c-53 0-96 43-96 96s43 96 96 96 96-43 96-96-43-96-96-96zm0 144c-26.5 0-48-21.5-48-48s21.5-48 48-48 48 21.5 48 48-21.5 48-48 48zm0-240C111 8 0 119 0 256s111 248 248 248 248-111 248-248S385 8 248 8zm0 448c-49.7 0-95.1-18.3-130.1-48.4 14.9-23 40.4-38.6 69.6-39.5 20.8 6.4 40.6 9.6 60.5 9.6s39.7-3.1 60.5-9.6c29.2 1 54.7 16.5 69.6 39.5-35 30.1-80.4 48.4-130.1 48.4zm162.7-84.1c-24.4-31.4-62.1-51.9-105.1-51.9-10.2 0-26 9.6-57.6 9.6-31.5 0-47.4-9.6-57.6-9.6-42.9 0-80.6 20.5-105.1 51.9C61.9 339.2 48 299.2 48 256c0-110.3 89.7-200 200-200s200 89.7 200 200c0 43.2-13.9 83.2-37.3 115.9z" /></svg></button>
          <a
            href="#."
            class="ml-2 hover:underline text-white hover:text-green-600">Preethi</a>
          <button class="ml-4 border-gray-900"><svg
              viewBox="0 0 24 24"
              width="24"
              height="24"
              class="fill-current text-gray-400 border-gray-900
                hover:text-green-600 w-6 h-6"><path
                d="M15.3 9.3a1 1 0 011.4 1.4l-4 4a1 1 0 01-1.4 0l-4-4a1 1 0 011.4-1.4l3.3 3.29 3.3-3.3z"
                class="heroicon-ui" /></svg></button>
        </div>
      </div>
      <div class="top-bar overflow-y-auto">
        <div class="container mx-auto">
          <h2 class="mt-24 text-5xl font-semibold text-white">Home</h2>
          <div class="mt-12">
            <h3 class="font-semibold text-xl border-b border-gray-300 pb-2">
              Recently Played
            </h3>
            <div class="flex items-center mt-4 -mx-4">
              <div class="w-1/5 px-4">
                <div>
                  <a href="#."><img
                      src="https://tailwind-v1-examples.netlify.app/albumcover03.jpg"
                      alt="album cover" /></a>
                </div>
                <div>
                  <a
                    href="#."
                    class="font-semibold block hover:text-green-600 mt-2">
                    Acoustic Pop Covers</a>
                </div>
                <div class="text-gray-500 mt-2">
                  Amazing Acoustic Covers Updated every week
                </div>
                <div
                  class="uppercase tracking-widest text-xs text-gray-500 mt-2">
                  6679 followers
                </div>
              </div>
              
              <div class="w-1/5 px-4">
                <div>
                  <a href="#."><img
                      src="https://tailwind-v1-examples.netlify.app/albumcover02.jpg"
                      alt="album cover" /></a>
                </div>
                <div>
                  <a
                    href="#."
                    class="font-semibold block hover:text-green-600 mt-2">
                    Acoustic Pop Covers</a>
                </div>
                <div class="text-gray-500 mt-2">
                  Amazing Acoustic Covers Updated every week
                </div>
                <div
                  class="uppercase tracking-widest text-xs text-gray-500 mt-2">
                  6679 followers
                </div>
              </div>
              <div class="w-1/5 px-4">
                <div>
                  <a href="#."><img
                      src="https://tailwind-v1-examples.netlify.app/albumcover05.jpg"
                      alt="album cover" /></a>
                </div>
                <div>
                  <a
                    href="#."
                    class="font-semibold block hover:text-green-600 mt-2">
                    Acoustic Pop Covers</a>
                </div>
                <div class="text-gray-500 mt-2">
                  Amazing Acoustic Covers Updated every week
                </div>
                <div
                  class="uppercase tracking-widest text-xs text-gray-500 mt-2">
                  6679 followers
                </div>
              </div>
              <div class="w-1/5 px-4">
                <div>
                  <a href="#."><img
                      src="https://tailwind-v1-examples.netlify.app/albumcover04.jpg"
                      alt="album cover" /></a>
                </div>
                <div>
                  <a
                    href="#."
                    class="font-semibold block hover:text-green-600 mt-2">
                    Acoustic Pop Covers</a>
                </div>
                <div class="text-gray-500 mt-2">
                  Amazing Acoustic Covers Updated every week
                </div>
                <div
                  class="uppercase tracking-widest text-xs text-gray-500 mt-2">
                  6679 followers
                </div>
              </div>
              <div class="w-1/5 px-4">
                <div>
                  <a href="#."><img
                      src="https://tailwind-v1-examples.netlify.app/albumcover06.jpg"
                      alt="album cover" /></a>
                </div>
                <div>
                  <a
                    href="#."
                    class="font-semibold block hover:text-green-600 mt-2">
                    Acoustic Pop Covers</a>
                </div>
                <div class="text-gray-500 mt-2">
                  Amazing Acoustic Covers Updated every week
                </div>
                <div
                  class="uppercase tracking-widest text-xs text-gray-500 mt-2">
                  6679 followers
                </div>
              </div>
            </div>
            <h3 class="font-semibold text-xl border-b border-gray-300 pb-2 mt-12">
              Made For You </h3>
            <div class="flex items-center mt-4 -mx-4">
              <div class="w-1/5 px-4">
                <div>
                  <a href="#."><img
                      src="https://tailwind-v1-examples.netlify.app/albumcover05.jpg"
                      alt="album cover" /></a>
                </div>
                <div>
                  <a
                    href="#."
                    class="font-semibold block hover:text-green-600 mt-2">
                    Acoustic Pop Covers</a>
                </div>
                <div class="text-gray-500 mt-2">
                  Amazing Acoustic Covers Updated every week
                </div>
                <div
                  class="uppercase tracking-widest text-xs text-gray-500 mt-2">
                  6679 followers
                </div>
              </div>
              <div class="w-1/5 px-4">
                <div>
                  <a href="#."><img
                      src="https://tailwind-v1-examples.netlify.app/albumcover03.jpg"
                      alt="album cover" /></a>
                </div>
                <div>
                  <a
                    href="#."
                    class="font-semibold block hover:text-green-600 mt-2">
                    Acoustic Pop Covers</a>
                </div>
                <div class="text-gray-500 mt-2">
                  Amazing Acoustic Covers Updated every week
                </div>
                <div
                  class="uppercase tracking-widest text-xs text-gray-500 mt-2">
                  6679 followers
                </div>
              </div>
              <div class="w-1/5 px-4">
                <div>
                  <a href="#."><img
                      src="https://tailwind-v1-examples.netlify.app/albumcover04.jpg"
                      alt="album cover" /></a>
                </div>
                <div>
                  <a
                    href="#."
                    class="font-semibold block hover:text-green-600 mt-2">
                    Acoustic Pop Covers</a>
                </div>
                <div class="text-gray-500 mt-2">
                  Amazing Acoustic Covers Updated every week
                </div>
                <div
                  class="uppercase tracking-widest text-xs text-gray-500 mt-2">
                  6679 followers
                </div>
              </div>
              <div class="w-1/5 px-4">
                <div>
                  <a href="#."><img
                      src="https://tailwind-v1-examples.netlify.app/albumcover06.jpg"
                      alt="album cover" /></a>
                </div>
                <div>
                  <a
                    href="#."
                    class="font-semibold block hover:text-green-600 mt-2">
                    Acoustic Pop Covers</a>
                </div>
                <div class="text-gray-500 mt-2">
                  Amazing Acoustic Covers Updated every week
                </div>
                <div
                  class="uppercase tracking-widest text-xs text-gray-500 mt-2">
                  6679 followers
                </div>
              </div>
              <div class="w-1/5 px-4">
                <div>
                  <a href="#."><img
                      src="https://tailwind-v1-examples.netlify.app/albumcover02.jpg"
                      alt="album cover" /></a>
                </div>
                <div>
                  <a
                    href="#."
                    class="font-semibold block hover:text-green-600 mt-2">
                    Acoustic Pop Covers</a>
                </div>
                <div class="text-gray-500 mt-2">
                  Amazing Acoustic Covers Updated every week
                </div>
                <div
                  class="uppercase tracking-widest text-xs text-gray-500 mt-2">
                  6679 followers
                </div>
              </div>
            </div>
            <h3 class="font-semibold text-xl border-b border-gray-300 pb-2 mt-12">
              Uniquely Yours
            </h3>
            <div class="flex items-center mt-4 -mx-4 mb-4">
              <div class="w-1/5 px-4">
                <div>
                  <a href="#."><img
                      src="https://tailwind-v1-examples.netlify.app/albumcover03.jpg"
                      alt="album cover" /></a>
                </div>
                <div>
                  <a
                    href="#."
                    class="font-semibold block hover:text-green-600 mt-2">
                    Acoustic Pop Covers</a>
                </div>
                <div class="text-gray-500 mt-2">
                  Amazing Acoustic Covers Updated every week
                </div>
                <div
                  class="uppercase tracking-widest text-xs text-gray-500 mt-2">
                  6679 followers
                </div>
              </div>
              <div class="w-1/5 px-4">
                <div>
                  <a href="#."><img
                      src="https://tailwind-v1-examples.netlify.app/albumcover06.jpg"
                      alt="album cover" /></a>
                </div>
                <div>
                  <a
                    href="#."
                    class="font-semibold block hover:text-green-600 mt-2">
                    Acoustic Pop Covers</a>
                </div>
                <div class="text-gray-500 mt-2">
                  Amazing Acoustic Covers Updated every week
                </div>
                <div
                  class="uppercase tracking-widest text-xs text-gray-500 mt-2">
                  6679 followers
                </div>
              </div>
              <div class="w-1/5 px-4">
                <div>
                  <a href="#."><img
                      src="https://tailwind-v1-examples.netlify.app/albumcover05.jpg"
                      alt="album cover" /></a>
                </div>
                <div>
                  <a
                    href="#."
                    class="font-semibold block hover:text-green-600 mt-2">
                    Acoustic Pop Covers</a>
                </div>
                <div class="text-gray-500 mt-2">
                  Amazing Acoustic Covers Updated every week
                </div>
                <div
                  class="uppercase tracking-widest text-xs text-gray-500 mt-2">
                  6679 followers
                </div>
              </div>
              <div class="w-1/5 px-4">
                <div>
                  <a href="#."><img
                      src="https://tailwind-v1-examples.netlify.app/albumcover02.jpg"
                      alt="album cover" /></a>
                </div>
                <div>
                  <a
                    href="#."
                    class="font-semibold block hover:text-green-600 mt-2">
                    Acoustic Pop Covers</a>
                </div>
                <div class="text-gray-500 mt-2">
                  Amazing Acoustic Covers Updated every week
                </div>
                <div
                  class="uppercase tracking-widest text-xs text-gray-500 mt-2">
                  6679 followers
                </div>
              </div>
              <div class="w-1/5 px-4">
                <div>
                  <a href="#."><img
                      src="https://tailwind-v1-examples.netlify.app/albumcover04.jpg"
                      alt="album cover" /></a>
                </div>
                <div>
                  <a
                    href="#."
                    class="font-semibold block hover:text-green-600 mt-2">
                    Acoustic Pop Covers</a>
                </div>
                <div class="text-gray-500 mt-2">
                  Amazing Acoustic Covers Updated every week
                </div>
                <div
                  class="uppercase tracking-widest text-xs text-gray-500 mt-2">
                  6679 followers
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div
    class="bg-gray-700 flex-none h-22 px-5 flex items-center justify-between">
    <div class="flex items-center">
      <a href="#.">
        <img
          src="https://tailwind-v1-examples.netlify.app/albumcover01.jpg"
          alt="album cover"
          class="w-12 h-12" /></a>
      <div class="ml-3">
        <div>
          <a href="#." class="hover:underline hover:text-green-600">Name of the
            Song</a>
        </div>
        <div>
          <a
            href="#."
            class="text-xs text-gray-600 hover:underline hover:text-green-600">Artist
            Name</a>
        </div>
      </div>
    </div>
    <div class="player-controls flex flex-col justify-center">
      <div class="flex justify-center mt-2">
        <button class="ml-2 px-2"><svg
            viewBox="0 0 20 20"
            class="fill-current text-gray-400 hover:text-white h-4 w-4"><path
              d="M6.59 12.83L4.4 15c-.58.58-1.59 1-2.4 1H0v-2h2c.29 0 .8-.2 1-.41l2.17-2.18 1.42 1.42zM16 4V1l4 4-4 4V6h-2c-.29 0-.8.2-1 .41l-2.17 2.18L9.4 7.17 11.6 5c.58-.58 1.59-1 2.41-1h2zm0 10v-3l4 4-4 4v-3h-2c-.82 0-1.83-.42-2.41-1l-8.6-8.59C2.8 6.21 2.3 6 2 6H0V4h2c.82 0 1.83.42 2.41 1l8.6 8.59c.2.2.7.41.99.41h2z" /></svg></button>
        <button class="ml-2 px-2"><svg
            class="fill-current text-gray-400 hover:text-green-600 h-5 w-5"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg">
            <path
              d="M12.0665 11.2C11.5332 11.6 11.5332 12.4 12.0665 12.8L17.3998 16.8C18.0591 17.2944 18.9998 16.824 18.9998 16V7.99999C18.9998 7.17594 18.0591 6.70556 17.3998 7.19999L12.0665 11.2Z"
              stroke="#374151"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round" />
            <path
              d="M4.0665 11.2C3.53317 11.6 3.53317 12.4 4.0665 12.8L9.39984 16.8C10.0591 17.2944 10.9998 16.824 10.9998 16V7.99998C10.9998 7.17594 10.0591 6.70556 9.39984 7.19998L4.0665 11.2Z"
              stroke="#374151"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round" />
          </svg></button>
        <button class="ml-2 px-2"><svg
            viewBox="0 0 20 20"
            class="fill-current text-gray-400 hover:text-white h-8 w-8"><path
              d="M2.93 17.07A10 10 0 1117.07 2.93 10 10 0 012.93 17.07zm12.73-1.41A8 8 0 104.34 4.34a8 8 0 0011.32 11.32zM7 6l8 4-8 4V6z" /></svg></button>

        <button class="ml-2 px-2"><svg
            class="fill-current text-gray-400 hover:text-green-600 h-5 w-5"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg">
            <path
              d="M11.9333 12.8C12.4667 12.4 12.4667 11.6 11.9333 11.2L6.6 7.19998C5.94076 6.70556 5 7.17594 5 7.99998L5 16C5 16.824 5.94076 17.2944 6.6 16.8L11.9333 12.8Z"
              stroke="#374151"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round" />
            <path
              d="M19.9333 12.8C20.4667 12.4 20.4667 11.6 19.9333 11.2L14.6 7.19998C13.9408 6.70556 13 7.17594 13 7.99998L13 16C13 16.824 13.9408 17.2944 14.6 16.8L19.9333 12.8Z"
              stroke="#374151"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round" />
          </svg></button>
        <button class="ml-2 px-2"><svg
            viewBox="0 0 24 24"
            width="24"
            height="24"
            class="fill-current text-gray-400 hover:text-white h-4 w-4"><path
              d="M5.41 16H18a2 2 0 002-2 1 1 0 012 0 4 4 0 01-4 4H5.41l2.3 2.3a1 1 0 01-1.42 1.4l-4-4a1 1 0 010-1.4l4-4a1 1 0 111.42 1.4L5.4 16zM6 8a2 2 0 00-2 2 1 1 0 01-2 0 4 4 0 014-4h12.59l-2.3-2.3a1 1 0 111.42-1.4l4 4a1 1 0 010 1.4l-4 4a1 1 0 01-1.42-1.4L18.6 8H6z" /></svg></button>
      </div>
      <div class="flex items-center justify-center">
        <div>1:20</div>
        <div class="bg-gray-400 rounded-lg w-64 xl:w-72 h-1 ml-3" />
        <div class="ml-3">3:20</div>
      </div>
    </div>
    <div class="volume-controls flex items-center">
      <button class="ml-4 px-2"><svg
          width="24"
          height="24"
          viewBox="0 0 24 24"
          class="fill-current text-gray-400 hover:text-green-600 h-6 w-6"><path
            d="M0 0h24v24H0z"
            fill="none" />
          <path
            d="M15 6H3v2h12V6zm0 4H3v2h12v-2zM3 16h8v-2H3v2zM17 6v8.18c-.31-.11-.65-.18-1-.18-1.66 0-3 1.34-3 3s1.34 3 3 3 3-1.34 3-3V8h3V6h-5z" /></svg></button>
      <svg
        width="24"
        height="24"
        viewBox="0 0 24 24"
        class="fill-current text-gray-400 hover:text-green-600 h-5 w-5"><path
          d="M3 9v6h4l5 5V4L7 9H3zm13.5 3A4.5 4.5 0 0014 7.97v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77s-2.99-7.86-7-8.77z" />
        <path d="M0 0h24v24H0z" fill="none" /></svg>
      <div class="bg-gray-400 rounded-lg w-12 h-1 ml-3" />
      <button class="ml-4 px-2"><svg
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
          class="fill-current text-gray-400 hover:text-green-600 h-4 w-4"><path
            d="M15 3h6v6M9 21H3v-6M21 3l-7 7M3 21l7-7" /></svg></button>
    </div>
  </div>
</div>
