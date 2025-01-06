<template>
  <section class="py-16">
    <div
      class="container mx-auto px-4 flex flex-col md:flex-row items-center relative"
    >
      <!-- Text Section -->
      <div class="md:w-1/2 z-10">
        <h2 class="text-xl text-gray-700">
          Best Destinations around the world
        </h2>
        <h1 class="text-4xl md:text-5xl font-bold text-blue-900 mt-2">
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
      <div class="md:w-1/2 mt-8 md:mt-0 relative z-20">
        <img class="w-full" src="/public/assets/Traveller.png" alt="Traveler" />
        <!-- Plane Animations -->
        <div class="plane plane-up">
          <img
            class="w-12 md:w-16"
            src="/public/assets/Icons/Plane.png"
            alt="plane"
          />
        </div>
        <div class="plane plane-down">
          <img
            class="w-12 md:w-16"
            src="/public/assets/Icons/Plane.png"
            alt="plane"
          />
        </div>
      </div>
    </div>
  </section>
</template>

<script setup></script>

<style lang="scss" scoped>
.container {
  position: relative;
}

.plane {
  position: absolute;
  top: 20%;
  width: 50px;
  animation-iteration-count: infinite;
  animation-timing-function: linear;
}

.plane img {
  display: block;
}

.plane-up {
  left: -10%;
  animation-name: flyRightUp;
  animation-duration: 25s;
  animation-delay: 0s;
}

.plane-down {
  left: -15%;
  top: 40%;
  animation-name: flyRightDown;
  animation-duration: 30s;
  animation-delay: 5s;
  transform: rotate(45deg);
}

@keyframes flyRightUp {
  0% {
    transform: translate(0, 0) rotate(0deg);
    opacity: 0;
  }
  10% {
    opacity: 1;
  }
  50% {
    transform: translate(110vw, -50vh) rotate(360deg);
    opacity: 1;
  }
  60% {
    opacity: 0;
  }
  100% {
    transform: translate(110vw, -50vh) rotate(360deg);
    opacity: 0;
  }
}

@keyframes flyRightDown {
  0% {
    transform: translate(0, 0) rotate(0deg);
    opacity: 0;
  }
  10% {
    opacity: 1;
  }
  50% {
    transform: translate(110vw, 50vh) rotate(-360deg);
    opacity: 1;
  }
  60% {
    opacity: 0;
  }
  100% {
    transform: translate(110vw, 50vh) rotate(-360deg);
    opacity: 0;
  }
}

/* Responsive Adjustments */
@media (min-width: 768px) {
  .plane {
    width: 70px;
  }

  .plane-up {
    animation-duration: 20s;
  }

  .plane-down {
    animation-duration: 25s;
  }
}
</style>
