<template>
  <section class="bg-white py-16">
    <div class="container mx-auto px-4">
      <!-- Section Title -->
      <h3 class="text-gray-500 uppercase tracking-wider text-center">
        Testimonials
      </h3>
      <h2 class="text-center text-4xl font-bold text-blue-900 mt-2">
        What People Say About Us.
      </h2>

      <!-- Testimonials Content -->
      <div
        class="mt-10 flex flex-col md:flex-row items-center justify-center space-y-8 md:space-y-0 md:space-x-8"
      >
        <!-- Testimonial Card -->
        <div class="bg-white rounded-lg shadow-lg p-6 w-full md:w-2/3 relative">
          <p class="text-gray-500 text-lg italic">
            "On the Windows talking painted posture yet its express parties use.
            Sure last upon he same as knew next. Of believed or diverted no."
          </p>
          <div class="mt-4 flex items-center space-x-4">
            <img
              src="/public/assets/Icons/Plane.png"
              alt="Mike Taylor"
              class="w-12 h-12 rounded-full object-cover"
            />
            <div>
              <h4 class="text-blue-900 font-bold">Mike Taylor</h4>
              <p class="text-gray-500 text-sm">Lahore, Pakistan</p>
            </div>
          </div>
          <div class="absolute bottom-4 right-4">
            <p class="text-gray-400 text-sm">Chris Thomas</p>
            <p class="text-gray-500 text-xs">CEO of Red Button</p>
          </div>
        </div>
      </div>

      <!-- Carousel Indicators -->
      <div class="mt-6 flex justify-center">
        <div class="w-3 h-3 bg-gray-400 rounded-full mx-1"></div>
        <div class="w-3 h-3 bg-gray-400 rounded-full mx-1"></div>
        <div class="w-3 h-3 bg-blue-900 rounded-full mx-1"></div>
      </div>
    </div>
  </section>
</template>

<script setup></script>

<style scoped></style>
