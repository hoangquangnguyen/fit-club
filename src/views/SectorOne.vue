<template>
  <div class="relative flex flex-row h-[700px]">
    <!-- area background -->
    <div
      class="absolute w-[450px] h-[450px] opacity-50 rounded-1/2 bg-orange-600 blur-[210px] -z-10"
    ></div>
    <!-- left -->
    <div class="w-full m-8">
      <div class="flex flex-row items-center justify-between">
        <div>
          <img src="@/assets/image/logo.png" alt="" class="h-12 w-40" />
        </div>
        <div>
          <ul class="flex flex-row items-center gap-2 text-xl gap-x-8">
            <li class="hover:text-orange-500"><a href="">Home</a></li>
            <li class="hover:text-orange-500"><a href="">Programs</a></li>
            <li class="hover:text-orange-500"><a href="">Why us</a></li>
            <li class="hover:text-orange-500"><a href="">Plans</a></li>
            <li class="hover:text-orange-500"><a href="">Testimonials</a></li>
          </ul>
        </div>
      </div>
      <div class="flex flex-col items-start mt-20">
        <div class="relative mb-8 p-3">
          <div
            class="absolute top-0 left-0 h-full w-full p-2 rounded-full bg-gray-800 z-0"
          >
            <div
              class="w-[125px] h-full bg-orange-500 rounded-full z-10 hover:transition hover:translate-x-full"
            ></div>
          </div>
          <span class="relative text-2xl z-20"
            >THE BEST FITNESS CLUB IN THE TOWN</span
          >
        </div>
        <div class="flex flex-col items-start mb-4">
          <h1
            class="text-7xl font-bold max-w-[500px] leading-tight mb-4 text-left"
          >
            SHAPE YOUR IDEAL BODY
          </h1>
          <p class="text-lg font-semibold">
            In here we will help you to shape and build your ideal body and live
            up your life to fullest
          </p>
        </div>
        <div class="flex flex-row items-center gap-x-8 mb-4">
          <div class="flex flex-col items-start justify-center">
            <span class="text-3xl font-medium">+ 140</span>
            <span class="text-gray-300">EXPERT COACHES</span>
          </div>
          <div class="flex flex-col items-start justify-center">
            <span class="text-3xl font-medium">+ 978</span>
            <span class="text-gray-300">MEMBERS JOINED</span>
          </div>
          <div class="flex flex-col items-start justify-center">
            <span class="text-3xl font-medium">+ 50</span>
            <span class="text-gray-300">FITNESS PROGRAMS</span>
          </div>
          <div
            class="flex flex-row items-center bg-gray-600 rounded-lg p-2 gap-x-3"
          >
            <img src="@/assets/image/calories.png" alt="" />
            <div class="flex flex-col items-start">
              <span class="text-gray-400 mb-5">Calories burned</span>
              <span class="text-white text-2xl">220 kcal</span>
            </div>
          </div>
        </div>
        <div>
          <button
            class="px-5 py-2 bg-orange-500 border-4 border-orange-500 text-white font-semibold"
          >
            Get Started
          </button>
          <button
            class="ml-5 px-5 py-2 bg-transparent border-4 border-orange-500 text-white font-semibold"
          >
            Learn More
          </button>
        </div>
      </div>
    </div>

    <!-- right -->
    <div
      class="relative w-[400px] h-full bg-gradient-to-b from-orange-600 via-orange-500 to-orange-400"
    >
      <button class="bg-white font-bold text-black px-5 py-2 mt-8">
        Join Now
      </button>
      <div class="absolute -left-[60%] bottom-0">
        <img
          src="@/assets/image/hero_image.png"
          alt=""
          class="h-[500px] w-[370px]"
        />
      </div>
      <div class="absolute right-1/4 top-[100px] bg-gray-600 rounded-lg p-3">
        <img src="@/assets/image/heart.png" alt="" class="h-[30px] w-[30px]" />
        <div class="flex flex-col items-start gap-y-3 mt-3">
          <span class="text-gray-500 font-bold">Heart Rate</span>
          <span class="text-2xl">116 bpm</span>
        </div>
      </div>
    </div>
  </div>
</template>
<script lang="ts">
export default {
  setup() {
    return {};
  },
};
</script>
