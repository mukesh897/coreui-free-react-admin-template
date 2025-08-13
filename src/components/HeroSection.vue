<template>
  <section class="relative isolate overflow-hidden bg-gradient-to-b from-[#FFF3EA] via-[#FFF9F5] to-white">
    <div class="absolute inset-0 -z-10" aria-hidden="true">
      <img
        class="w-full h-full object-cover opacity-25"
        src="https://images.unsplash.com/photo-1501785888041-af3ef285b470?q=80&w=1600&auto=format&fit=crop"
        alt="City skyline"
      />
      <div class="absolute inset-0 bg-white/60"></div>
    </div>

    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 pt-20 pb-16">
      <div class="text-center">
        <h1
          class="text-[40px] sm:text-[56px] md:text-[64px] lg:text-[72px] font-extrabold leading-[1.05] tracking-tight text-gray-900"
        >
          <span class="text-gray-900">0% Brokerage.</span>
          <span class="text-brand"> 100% Happiness</span>
        </h1>
        <p class="mt-3 text-base sm:text-lg md:text-xl text-gray-700">
          Find better places to live, work and wonder
        </p>
      </div>

      <div class="mt-8 mx-auto w-full max-w-[920px]">
        <!-- Segmented control -->
        <div
          class="mx-auto w-full max-w-[620px] flex rounded-[16px] border border-orange-200 bg-white/90 shadow-sm overflow-hidden backdrop-blur-[2px]"
        >
          <button
            class="flex-1 py-3 md:py-3.5 px-5 text-sm md:text-base font-semibold text-gray-900 bg-orange-50 border-r border-orange-200"
          >
            Residential
          </button>
          <button
            class="flex-1 py-3 md:py-3.5 px-5 text-sm md:text-base text-gray-600"
          >
            Commercial <span class="ml-1 text-xs text-brand">Coming soon...</span>
          </button>
        </div>

        <!-- Search row -->
        <div class="mt-4 flex items-stretch gap-3">
          <div
            class="flex-1 flex items-center gap-3 rounded-full border border-gray-200 bg-white px-4 py-2.5 shadow-sm"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
              class="w-5 h-5 text-gray-400"
            >
              <path
                fill-rule="evenodd"
                d="M10.5 3.75a6.75 6.75 0 1 0 0 13.5 6.75 6.75 0 0 0 0-13.5ZM2.25 10.5a8.25 8.25 0 1 1 14.71 5.053l4.243 4.243a.75.75 0 1 1-1.06 1.06l-4.243-4.242A8.25 8.25 0 0 1 2.25 10.5Z"
                clip-rule="evenodd"
              />
            </svg>
            <input
              placeholder="Search for locality, landmark, project or builder"
              class="flex-1 outline-none bg-transparent text-sm md:text-base py-1.5 placeholder-gray-500"
            />
          </div>
          <button
            class="h-[46px] md:h-[48px] px-6 md:px-8 rounded-full bg-brand text-white font-semibold shadow-sm hover:bg-brand-600 transition"
          >
            Search
          </button>
        </div>

        <!-- Popular localities -->
        <div class="mt-5">
          <div class="text-sm md:text-base text-gray-700 font-medium flex items-center gap-2">
            <span>Popular Localities</span>
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-brand">
              <path d="M16.5 6.75a.75.75 0 0 1 .75.75v9a.75.75 0 0 1-1.28.53l-3.97-3.97a.75.75 0 0 1 0-1.06l3.97-3.97a.75.75 0 0 1 .53-.22Z"/>
              <path d="M6.75 6.75a.75.75 0 0 1 .75.75v9a.75.75 0 0 1-1.5 0v-9a.75.75 0 0 1 .75-.75Z"/>
            </svg>
          </div>
          <div class="mt-3 flex flex-wrap items-center gap-2">
            <button class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-full border border-gray-200 bg-white text-sm shadow-sm hover:border-brand transition">
              Wakad
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-gray-500">
                <path fill-rule="evenodd" d="M8.47 4.97a.75.75 0 0 1 1.06 0l6 6a.75.75 0 0 1 0 1.06l-6 6a.75.75 0 1 1-1.06-1.06L13.94 12 8.47 6.53a.75.75 0 0 1 0-1.06Z" clip-rule="evenodd"/>
              </svg>
            </button>
            <button class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-full border border-gray-200 bg-white text-sm shadow-sm hover:border-brand transition">
              Kharadi
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-gray-500">
                <path fill-rule="evenodd" d="M8.47 4.97a.75.75 0 0 1 1.06 0l6 6a.75.75 0 0 1 0 1.06l-6 6a.75.75 0 1 1-1.06-1.06L13.94 12 8.47 6.53a.75.75 0 0 1 0-1.06Z" clip-rule="evenodd"/>
              </svg>
            </button>
            <button class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-full border border-gray-200 bg-white text-sm shadow-sm hover:border-brand transition">
              Baner
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-gray-500">
                <path fill-rule="evenodd" d="M8.47 4.97a.75.75 0 0 1 1.06 0l6 6a.75.75 0 0 1 0 1.06l-6 6a.75.75 0 1 1-1.06-1.06L13.94 12 8.47 6.53a.75.75 0 0 1 0-1.06Z" clip-rule="evenodd"/>
              </svg>
            </button>
            <button class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-full border border-gray-200 bg-white text-sm shadow-sm hover:border-brand transition">
              Hinjewadi
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-gray-500">
                <path fill-rule="evenodd" d="M8.47 4.97a.75.75 0 0 1 1.06 0l6 6a.75.75 0 0 1 0 1.06l-6 6a.75.75 0 1 1-1.06-1.06L13.94 12 8.47 6.53a.75.75 0 0 1 0-1.06Z" clip-rule="evenodd"/>
              </svg>
            </button>
            <button class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-full border border-gray-200 bg-white text-sm shadow-sm hover:border-brand transition">
              Viman Nagar
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-gray-500">
                <path fill-rule="evenodd" d="M8.47 4.97a.75.75 0 0 1 1.06 0l6 6a.75.75 0 0 1 0 1.06l-6 6a.75.75 0 1 1-1.06-1.06L13.94 12 8.47 6.53a.75.75 0 0 1 0-1.06Z" clip-rule="evenodd"/>
              </svg>
            </button>
            <button class="inline-flex items-center justify-center w-8 h-8 rounded-full bg-orange-100 text-brand hover:bg-orange-200 transition">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4">
                <path fill-rule="evenodd" d="M8.47 4.97a.75.75 0 0 1 1.06 0l6 6a.75.75 0 0 1 0 1.06l-6 6a.75.75 0 1 1-1.06-1.06L13.94 12 8.47 6.53a.75.75 0 0 1 0-1.06Z" clip-rule="evenodd"/>
              </svg>
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
</script>

<style scoped>
.text-brand { color: var(--color-brand); }
.bg-brand { background-color: var(--color-brand); }
.hover\:bg-brand-600:hover { background-color: var(--color-brand-600); }
</style>