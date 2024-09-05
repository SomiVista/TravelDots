<template>
  <section class="py-16">
    <div
      class="container mx-auto px-4 flex flex-col md:flex-row items-center relative"
    >
      <!-- Text Section -->
      <div class="md:w-1/2">
        <h2>Best Destinations around the world</h2>
        <h1 class="text-4xl md:text-5xl font-bold text-blue-900">
          Travel, enjoy <br />
          and live a new <br />
          and full life
        </h1>
        <p class="text-gray-500 mt-4">
          Built Wicket longer admire do barton vanity itself do in it. Preferred
          to sportsmen in engrossed listening. Park gate sell they west hard for
          the.
        </p>
        <div class="mt-6">
          <button
            class="bg-orange-500 text-white font-bold py-2 px-6 rounded-lg hover:bg-orange-600 transition"
          >
            Find out more
          </button>
          <button
            class="ml-4 text-orange-500 font-bold py-2 px-6 border border-orange-500 rounded-lg hover:bg-orange-500 hover:text-white transition"
          >
            Play Demo
          </button>
        </div>
      </div>
      <!-- Image Section -->

      <div class="plane up">
        <img src="/public/assets/Icons/Plane.png" alt="plane" />
      </div>
      <div class="md:w-1/2 mt-8 md:mt-0 z-20">
        <img src="/public/assets/Traveller.png" alt="Traveler" class="w-full" />
      </div>
      <div class="plane down">
        <img src="/public/assets/Icons/Plane.png" alt="plane" />
      </div>
    </div>
  </section>
</template>

<script setup></script>

<style lang="scss" scoped>
.plane {
  position: relative;
  animation: plane 10s linear 0s infinite reverse;
}
.up {
  top: -250px;
  right: -300px;
}
.down {
  top: -100px;
  right: -100px;
}

@keyframes plane {
  from {
    right: -500px;
  }
  to {
    right: 102%;
  }
}
</style>
