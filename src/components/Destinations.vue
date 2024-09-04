<template>
  <section class="bg-white py-16">
    <div class="container mx-auto px-4">
      <!-- Section Title -->
      <h3 class="text-center text-gray-500 uppercase tracking-wider">
        Top Selling
      </h3>
      <h2 class="text-center text-4xl font-bold text-blue-900 mt-2">
        Top Destinations
      </h2>

      <!-- Destinations Grid -->
      <div class="mt-10 grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-8">
        <!-- Destination Card 1 -->
        <div class="bg-white rounded-lg shadow-lg overflow-hidden">
          <img
            src="/public/assets/Destinations/Rome.png"
            alt="Rome, Italy"
            class="w-full h-48 object-cover"
          />
          <div class="p-4">
            <h3 class="text-lg font-semibold text-blue-900">Rome, Italy</h3>
            <p class="text-gray-500">$5,42k</p>
            <p class="text-sm text-gray-400 mt-2">10 Days Trip</p>
          </div>
        </div>

        <!-- Destination Card 2 -->
        <div class="bg-white rounded-lg shadow-lg overflow-hidden">
          <img
            src="/public/assets/Destinations/London.jpg"
            alt="London, UK"
            class="w-full h-48 object-cover"
          />
          <div class="p-4">
            <h3 class="text-lg font-semibold text-blue-900">London, UK</h3>
            <p class="text-gray-500">$4,2k</p>
            <p class="text-sm text-gray-400 mt-2">12 Days Trip</p>
          </div>
        </div>

        <!-- Destination Card 3 -->
        <div class="bg-white rounded-lg shadow-lg overflow-hidden">
          <img
            src="/public/assets/Destinations/Amsterdam.png"
            alt="Full Europe"
            class="w-full h-48 object-cover"
          />
          <div class="p-4">
            <h3 class="text-lg font-semibold text-blue-900">Amsterdam, NE</h3>
            <p class="text-gray-500">$15k</p>
            <p class="text-sm text-gray-400 mt-2">28 Days Trip</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup></script>

<style scoped></style>
