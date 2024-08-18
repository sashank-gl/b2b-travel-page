<template>
  <div
    class="xl:h-screen flex flex-col bg-gradient-to-br from-pink-200 via-pink-100 via-50% to-pink-50 p-6 xl:p-12"
  >
    <h2 class="text-4xl mb-4 font-semibold">Discover Jaipur's Hotspots</h2>
    <p class="text-sm sm:text-base">
      Explore the city's most iconic locations, from bustling markets to serene
      landmarks, and uncover the best spots to experience Jaipur like a local.
    </p>

    <div class="grow flex justify-center items-center">
      <div
        class="flex xl:flex-row flex-col items-center justify-center gap-12 py-12"
      >
        <!-- Image 1 -->
        <div
          class="relative w-64 h-96 cursor-pointer group rounded-xl overflow-hidden translate-x-0 sm:translate-x-24 xl:translate-x-0 xl:translate-y-6"
        >
          <div
            class="absolute inset-0 flex items-end justify-center bg-gradient-to-t from-pink-950/75 from-5% py-4 to-transparent text-white text-center text-xl font-semibold opacity-0 group-hover:opacity-100 z-10"
          >
            Hawa Mahal
          </div>
          <img
            src="https://images.unsplash.com/photo-1687372985044-a68b5fe7bd06?q=80&w=600"
            alt="Jaipur"
            class="object-cover group-hover:scale-110 w-full h-full transition-transform duration-1000 ease-in-out"
          />
        </div>

        <!-- Image 2 -->

        <div
          class="relative w-64 h-96 cursor-pointer group rounded-xl overflow-hidden translate-x-0 sm:-translate-x-24 xl:translate-x-0 xl:-translate-y-6"
        >
          <div
            class="absolute inset-0 flex items-end justify-center bg-gradient-to-t from-pink-950/75 from-5% py-4 to-transparent text-white text-center text-xl font-semibold opacity-0 group-hover:opacity-100 z-10"
          >
            Amber Palace
          </div>
          <img
            src="https://images.unsplash.com/photo-1688671141790-a17b0c866bb7?q=80&w=600"
            alt="Jaipur"
            class="object-cover group-hover:scale-110 w-full h-full transition-transform duration-1000 ease-in-out"
          />
        </div>

        <!-- Image 3 -->

        <div
          class="relative w-64 h-96 cursor-pointer group rounded-xl overflow-hidden translate-x-0 sm:translate-x-24 xl:translate-x-0 xl:translate-y-6"
        >
          <div
            class="absolute inset-0 flex items-end justify-center bg-gradient-to-t from-pink-950/75 from-5% py-4 to-transparent text-white text-center text-xl font-semibold opacity-0 group-hover:opacity-100 z-10"
          >
            Sundial
          </div>
          <img
            src="https://images.unsplash.com/photo-1660736701150-975a90ce2d9e?q=80&w=600"
            alt="Jaipur"
            class="object-cover group-hover:scale-110 w-full h-full transition-transform duration-1000 ease-in-out"
          />
        </div>

        <!-- Image 4 -->

        <div
          class="relative w-64 h-96 cursor-pointer group rounded-xl overflow-hidden translate-x-0 sm:-translate-x-24 xl:translate-x-0 xl:-translate-y-6"
        >
          <div
            class="absolute inset-0 flex items-end justify-center bg-gradient-to-t from-pink-950/75 from-5% py-4 to-transparent text-white text-center text-xl font-semibold opacity-0 group-hover:opacity-100 z-10"
          >
            Local Market
          </div>
          <img
            src="https://images.unsplash.com/photo-1645944235766-54aade0e09bf?q=80&w=600"
            alt="Jaipur"
            class="object-cover group-hover:scale-110 w-full h-full transition-transform duration-1000 ease-in-out"
          />
        </div>
      </div>
    </div>
  </div>
</template>
