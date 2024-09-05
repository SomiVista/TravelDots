<template>
  <section class="py-16">
    <div
      class="container mx-auto px-4 flex flex-col md:flex-row items-center justify-between"
    >
      <!-- Text Section -->
      <div class="md:w-1/2">
        <h3 class="text-gray-500 uppercase tracking-wider">Easy and Fast</h3>
        <h2 class="text-4xl font-bold text-blue-900 mt-2">
          Book Your Next Trip <br />
          In 3 Easy Steps
        </h2>
        <!-- Steps -->
        <div class="mt-8 space-y-6">
          <!-- Step 1 -->
          <div class="flex items-start">
            <div
              class="w-12 h-12 bg-yellow-400 rounded-full flex items-center justify-center text-white font-bold"
            >
              1
            </div>
            <div class="ml-4">
              <h4 class="text-lg font-semibold text-blue-900">
                Choose Destination
              </h4>
              <p class="text-gray-500">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Urna,
                tortor tempus.
              </p>
            </div>
          </div>

          <!-- Step 2 -->
          <div class="flex items-start">
            <div
              class="w-12 h-12 bg-red-400 rounded-full flex items-center justify-center text-white font-bold"
            >
              2
            </div>
            <div class="ml-4">
              <h4 class="text-lg font-semibold text-blue-900">Make Payment</h4>
              <p class="text-gray-500">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Urna,
                tortor tempus.
              </p>
            </div>
          </div>

          <!-- Step 3 -->
          <div class="flex items-start">
            <div
              class="w-12 h-12 bg-blue-400 rounded-full flex items-center justify-center text-white font-bold"
            >
              3
            </div>
            <div class="ml-4">
              <h4 class="text-lg font-semibold text-blue-900">
                Reach Airport on Selected Date
              </h4>
              <p class="text-gray-500">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Urna,
                tortor tempus.
              </p>
            </div>
          </div>
        </div>
      </div>

      <!-- Image Section -->
      <div class="md:w-1/2 mt-10 md:mt-0">
        <div class="relative">
          <img
            src="/public/assets/Destinations/Greece.jpg"
            alt="Trip to Greece"
            class="w-full rounded-lg shadow-lg"
          />
          <div
            class="absolute bottom-4 left-4 bg-white p-4 rounded-lg shadow-lg"
          >
            <h4 class="text-blue-900 font-bold">Trip To Greece</h4>
            <p class="text-gray-500 text-sm">14-29 June | by Robbin Joe</p>
            <div class="flex items-center space-x-2 mt-2">
              <span class="text-gray-500 text-sm">24 people going</span>
              <span class="text-blue-500 text-sm">Ongoing</span>
            </div>
          </div>
          <div
            class="absolute top-4 right-4 bg-white p-2 rounded-full shadow-lg"
          >
            <p class="text-gray-500 text-sm">Trip to Rome</p>
            <p class="text-blue-500 text-sm font-bold">40% completed</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup></script>

<style scoped></style>
