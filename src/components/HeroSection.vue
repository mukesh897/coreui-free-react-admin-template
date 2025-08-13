<template>
  <section class="relative isolate bg-white">
    <div class="absolute inset-0 -z-10" aria-hidden="true">
      <img class="w-full h-full object-cover opacity-30" src="https://images.unsplash.com/photo-1501785888041-af3ef285b470?q=80&w=1600&auto=format&fit=crop" alt="Mountain lake" />
      <div class="absolute inset-0 bg-white/70"></div>
    </div>

    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 pt-16 pb-10">
      <div class="text-center">
        <h1 class="text-4xl sm:text-6xl md:text-7xl font-extrabold tracking-tight text-gray-900">
          Turning Properties into Prosperity.
        </h1>
        <p class="mt-4 text-lg text-gray-700">From homes to investments, we help you unlock lasting value</p>
      </div>

      <div class="mt-8 mx-auto max-w-5xl">
        <div class="flex rounded-xl border border-gray-200 bg-white shadow-sm overflow-hidden">
          <button class="flex-1 py-3 font-semibold text-sm bg-gray-100">Residential</button>
          <button class="flex-1 py-3 font-semibold text-sm text-gray-500">Commercial</button>
        </div>

        <div class="mt-3 grid grid-cols-1 lg:grid-cols-2 gap-3">
          <div class="flex items-center gap-2 rounded-lg border border-gray-200 bg-white px-3 py-2 shadow-sm">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5 text-gray-400"><path fill-rule="evenodd" d="M10.5 3.75a6.75 6.75 0 1 0 0 13.5 6.75 6.75 0 0 0 0-13.5ZM2.25 10.5a8.25 8.25 0 1 1 14.71 5.053l4.243 4.243a.75.75 0 1 1-1.06 1.06l-4.243-4.242A8.25 8.25 0 0 1 2.25 10.5Z" clip-rule="evenodd"/></svg>
            <input placeholder="Search for locality, landmark, project or builder" class="flex-1 outline-none text-sm py-2" />
          </div>
          <div class="flex items-center gap-2 rounded-lg border border-gray-200 bg-white px-3 py-2 shadow-sm">
            <input placeholder="Search by location, project, or keyword" class="flex-1 outline-none text-sm py-2" />
          </div>
        </div>

        <div class="mt-5">
          <div class="text-sm text-gray-700 font-medium">Popular Localities</div>
          <div class="mt-2 flex flex-wrap gap-2">
            <span class="px-3 py-1 rounded-full border border-gray-200 bg-white text-sm">Whitefield</span>
            <span class="px-3 py-1 rounded-full border border-gray-200 bg-white text-sm">HSR</span>
            <span class="px-3 py-1 rounded-full border border-gray-200 bg-white text-sm">Koramangala</span>
            <span class="px-3 py-1 rounded-full border border-gray-200 bg-white text-sm">Banaswadi</span>
            <span class="px-3 py-1 rounded-full border border-gray-200 bg-white text-sm">JP Nagar</span>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
</script>