<template>
  <div
    class="relative h-screen flex flex-col justify-between bg-[url('https://images.unsplash.com/photo-1631987398000-e627564b3847?q=80&w=1080')] bg-cover bg-center px-6"
  >
    <div
      class="z-0 absolute inset-0 bg-gradient-to-tr from-pink-200 via-pink-100 via-50% to-pink-50/50"
    />

    <!-- Navbar -->

    <div class="z-10 flex h-20 w-full items-center justify-between">
      <h2 class="text-2xl font-bold">GoJaipur</h2>
      <nav class="hidden xl:flex items-center gap-6">
        <a href="" class="font-bold hover:underline hover:underline-offset-4"
          >Home</a
        >
        <a href="" class="font-bold hover:underline hover:underline-offset-4"
          >Destinations</a
        >
        <a href="" class="font-bold hover:underline hover:underline-offset-4"
          >Deals & Offers</a
        >
        <a href="" class="font-bold hover:underline hover:underline-offset-4"
          >Blog</a
        >
      </nav>
      <button
        class="hidden xl:block bg-pink-700 py-2 px-4 rounded-md font-semibold text-pink-50 hover:bg-pink-600"
      >
        Book Now
      </button>
    </div>

    <!-- Main Container -->

    <div
      class="z-10 flex flex-col-reverse xl:flex-row grow items-center justify-between md:justify-normal"
    >
      <!-- Hero Section -->

      <div
        class="h-full flex items-end xl:items-center justify-center w-full xl:w-1/2 py-10 xl:py-0"
      >
        <div class="flex flex-col items-start gap-4 xl:gap-6">
          <h2 class="text-3xl xl:text-6xl font-semibold">
            Unveil
            <span class="underline underline-offset-4 xl:underline-offset-8"
              >Jaipur's</span
            >
            Majesty
          </h2>
          <p class="mb-2 text-sm sm:text-base">
            Dive into the heart of Rajasthan and explore the royal heritage,
            vibrant markets, and architectural wonders of Jaipur. From the
            iconic Hawa Mahal to the bustling bazaars, experience the rich
            culture and history that Jaipur has to offer.
          </p>
          <button
            class="bg-pink-700 py-3 px-6 rounded-md font-semibold text-pink-50 hover:bg-pink-600 hover:shadow-2xl hover:shadow-pink-600"
          >
            Plan Your Trip
          </button>
        </div>
      </div>

      <!-- Images -->

      <div
        class="h-full flex mt-24 items-end xl:items-center justify-center w-full xl:w-1/2"
      >
        <div
          class="grid grid-rows-2 grid-flow-col place-content-center place-items-center gap-4 xl:gap-8"
        >
          <img
            src="https://images.unsplash.com/photo-1602643163983-ed0babc39797?q=80&w=600"
            alt="Hawa Mahal"
            class="image-animation-1 size-32 sm:size-48 xl:w-56 xl:h-64 rounded-xl object-cover"
          />
          <img
            src="https://images.unsplash.com/photo-1599661046289-e31897846e41?q=80&w=600
              "
            alt="Amber Fort"
            class="image-animation-2 size-28 sm:size-48 xl:w-56 xl:h-64 rounded-xl object-cover"
          />

          <img
            src="https://images.unsplash.com/photo-1716534134003-ba47907e119b?q=80&w=600
              "
            alt="City Palace"
            class="image-animation-3 w-32 h-40 sm:h-64 sm:w-48 xl:w-64 xl:h-80 rounded-xl object-cover row-span-2"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
@keyframes scaleFade {
  0% {
    transform: scale(0);
    opacity: 0;
  }
  50% {
    transform: scale(1.1);
    opacity: 1;
  }
  75% {
    transform: scale(0.9);
    opacity: 1;
  }
  100% {
    transform: scale(1);
    opacity: 1;
  }
}

.image-animation-1 {
  animation: scaleFade 1s ease-in-out 0s forwards;
  opacity: 0;
}
.image-animation-2 {
  animation: scaleFade 1s ease-in-out 0.2s forwards;
  opacity: 0;
}
.image-animation-3 {
  animation: scaleFade 1s ease-in-out 0.4s forwards;
  opacity: 0;
}
</style>
