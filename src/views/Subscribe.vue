<template>
  <div
    class="flex h-screen flex-col bg-gradient-to-tr from-pink-200 via-pink-100 via-50% to-pink-50 p-12"
  >
    <div class="flex grow items-center justify-center gap-6 flex-col">
      <h2 class="text-4xl xl:text-6xl font-semibold text-center">
        Subscribe for Exclusive Offers
      </h2>
      <p class="text-center max-w-2xl">
        Stay ahead of the game with special promotions and our monthly
        newsletter. Sign up now to never miss out on exciting updates and
        exclusive deals!
      </p>

      <div
        class="flex items-center gap-4 bg-white px-2 rounded-full pl-4 sm:pl-6 group border-4 border-transparent focus-within:border-pink-950"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 24 24"
          fill="currentColor"
          class="size-6"
        >
          <path
            d="M1.5 8.67v8.58a3 3 0 0 0 3 3h15a3 3 0 0 0 3-3V8.67l-8.928 5.493a3 3 0 0 1-3.144 0L1.5 8.67Z"
          />
          <path
            d="M22.5 6.908V6.75a3 3 0 0 0-3-3h-15a3 3 0 0 0-3 3v.158l9.714 5.978a1.5 1.5 0 0 0 1.572 0L22.5 6.908Z"
          />
        </svg>
        <input
          type="mail"
          placeholder="Your Email Here"
          class="py-3 w-40 sm:w-auto text-xl outline-none"
        />
        <button
          class="bg-pink-950 rounded-full py-2 px-6 text-pink-50 hover:bg-pink-900"
        >
          Subscribe
        </button>
      </div>
    </div>

    <div
      class="flex flex-col sm:flex-row w-full justify-between items-center text-center sm:text-left sm:items-start gap-10 sm:gap-0"
    >
      <h2 class="text-2xl font-bold">GoJaipur</h2>

      <div>
        <h2 class="mb-2 font-bold">Explore More</h2>
        <nav class="flex flex-col gap-1 sm:items-start">
          <a href="" class="font-semibold">About Us</a>
          <a href="" class="font-semibold">Currency Coverter</a>
          <a href="" class="font-semibold">Visa</a>
          <a href="" class="font-semibold">Contact</a>
        </nav>
      </div>

      <div>
        <h2 class="mb-2 font-bold">Other Destinations</h2>

        <nav class="flex flex-col gap-1 sm:items-start">
          <a href="" class="font-semibold">Agra</a>
          <a href="" class="font-semibold">Delhi</a>
          <a href="" class="font-semibold">Munnar</a>
          <a href="" class="font-semibold">Hyderabad</a>
        </nav>
      </div>

      <div class="flex items-center gap-4">
        <svg
          class="size-6"
          viewBox="0 0 15 15"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M7.5 5C6.11929 5 5 6.11929 5 7.5C5 8.88071 6.11929 10 7.5 10C8.88071 10 10 8.88071 10 7.5C10 6.11929 8.88071 5 7.5 5Z"
            fill="#500724"
          />
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M4.5 0C2.01472 0 0 2.01472 0 4.5V10.5C0 12.9853 2.01472 15 4.5 15H10.5C12.9853 15 15 12.9853 15 10.5V4.5C15 2.01472 12.9853 0 10.5 0H4.5ZM4 7.5C4 5.567 5.567 4 7.5 4C9.433 4 11 5.567 11 7.5C11 9.433 9.433 11 7.5 11C5.567 11 4 9.433 4 7.5ZM11 4H12V3H11V4Z"
            fill="#500724"
          />
        </svg>

        <svg
          fill="#000000"
          class="size-[26px]"
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
          data-name="Layer 1"
        >
          <path
            fill="#500724"
            d="M20.9,2H3.1A1.1,1.1,0,0,0,2,3.1V20.9A1.1,1.1,0,0,0,3.1,22h9.58V14.25h-2.6v-3h2.6V9a3.64,3.64,0,0,1,3.88-4,20.26,20.26,0,0,1,2.33.12v2.7H17.3c-1.26,0-1.5.6-1.5,1.47v1.93h3l-.39,3H15.8V22h5.1A1.1,1.1,0,0,0,22,20.9V3.1A1.1,1.1,0,0,0,20.9,2Z"
          />
        </svg>
      </div>
    </div>
  </div>
</template>
