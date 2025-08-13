<template>
  <section class="relative isolate min-h-[calc(100vh-4rem)] bg-[#fdebd9]">
    <!-- Background city skyline with warm overlay -->
    <div class="absolute inset-0 -z-10">
      <img class="w-full h-full object-cover opacity-30" src="https://images.unsplash.com/photo-1494526585095-c41746248156?q=80&w=1920&auto=format&fit=crop" alt="City skyline" />
      <div class="absolute inset-0 bg-gradient-to-b from-[#ffe9d3]/70 via-[#ffe9d3]/60 to-[#fffaf6]/90"></div>
    </div>

    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col pt-10 md:pt-14 pb-10 h-full">
      <!-- Headline -->
      <div class="mt-10 md:mt-16 text-center">
        <h1 class="text-[36px] sm:text-[44px] md:text-[54px] leading-[1.1] font-extrabold tracking-tight text-gray-900">
          <span>0%Brokerage.</span>
          <span class="ml-1">100%<span class="text-brand">Happiness</span></span>
        </h1>
        <p class="mt-4 text-[20px] text-gray-800">Find Better Places to Live, Work and Wonder</p>
      </div>

      <!-- Search panel -->
      <div class="mt-8 md:mt-10 mx-auto w-full max-w-4xl">
        <!-- Tabs -->
        <div class="mx-auto w-full max-w-[520px] rounded-2xl border border-[#f2b891] bg-white/70 shadow-sm overflow-hidden flex">
          <button class="flex-1 py-3 text-[15px] font-semibold text-gray-800 bg-white">Residential</button>
          <button class="flex-1 py-3 text-[15px] font-semibold text-gray-500 bg-white/40 relative">
            Commercial
            <span class="ml-1 align-middle text-xs text-gray-400">Coming soon...</span>
          </button>
        </div>

        <!-- Input row -->
        <div class="mt-3 flex items-stretch gap-2">
          <!-- Location pill (left) -->
          <button class="inline-flex items-center gap-2 px-3 h-[46px] rounded-xl border border-[#f2b891] bg-white/80 shadow-sm text-sm font-medium text-gray-700">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-brand"><path d="M12 2.25c-4.97 0-9 3.857-9 8.609 0 5.676 7.338 10.602 8.221 11.162.48.309 1.078.309 1.558 0 .883-.56 8.221-5.486 8.221-11.162 0-4.752-4.03-8.609-9-8.609Zm0 11.359a2.75 2.75 0 1 1 0-5.5 2.75 2.75 0 0 1 0 5.5Z"/></svg>
            <span>Pune</span>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4"><path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5"/></svg>
          </button>

          <!-- Search field -->
          <div class="flex-1 flex items-center gap-2 rounded-xl border border-[#f2b891] bg-white/80 px-3 h-[46px] shadow-sm">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5 text-gray-400"><path fill-rule="evenodd" d="M10.5 3.75a6.75 6.75 0 1 0 0 13.5 6.75 6.75 0 0 0 0-13.5ZM2.25 10.5a8.25 8.25 0 1 1 14.71 5.053l4.243 4.243a.75.75 0 1 1-1.06 1.06l-4.243-4.242A8.25 8.25 0 0 1 2.25 10.5Z" clip-rule="evenodd"/></svg>
            <input placeholder="Search for locality, landmark, project or builder" class="flex-1 outline-none text-sm placeholder:text-gray-500 bg-transparent" />
          </div>

          <!-- CTA -->
          <button class="px-5 md:px-6 rounded-xl bg-brand text-white font-semibold shadow-sm hover:bg-brand-600 h-[46px]">Search</button>
        </div>

        <!-- Popular localities -->
        <div class="mt-5">
          <div class="text-[15px] text-gray-800 font-semibold">Popular Localities <span class="align-middle">↗</span></div>
          <div class="mt-3 flex flex-wrap gap-2.5">
            <span class="inline-flex items-center gap-1 px-3 py-1.5 rounded-full border border-[#f2b891] bg-white/80 text-sm">Wakad <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4"><path d="m9 5 7 7-7 7"/></svg></span>
            <span class="inline-flex items-center gap-1 px-3 py-1.5 rounded-full border border-[#f2b891] bg-white/80 text-sm">Kharadi <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4"><path d="m9 5 7 7-7 7"/></svg></span>
            <span class="inline-flex items-center gap-1 px-3 py-1.5 rounded-full border border-[#f2b891] bg-white/80 text-sm">Baner <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4"><path d="m9 5 7 7-7 7"/></svg></span>
            <button class="inline-flex items-center justify-center w-7 h-7 rounded-full bg-brand text-white"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4"><path d="m9 5 7 7-7 7"/></svg></button>
          </div>
        </div>
      </div>

      <!-- Spacer to align visual center vertically -->
      <div class="flex-1"></div>
    </div>
  </section>
</template>

<script setup>
</script>