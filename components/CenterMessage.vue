<template>
  <div class="relative flex items-center justify-center min-h-screen">
    <div class="max-w-4xl mx-auto px-4 md:px-6">
      <nuxt-link
        class="flex justify-center pt-8 sm:pt-0"
        :to="{ name: 'index' }"
      >
        <ngoding-manusiawi-logo class="w-auto h-32" />
      </nuxt-link>
      <div class="mt-4 bg-white overflow-hidden shadow-lg rounded-lg p-6">
        <h1
          class="text-2xl leading-7 font-semibold text-center text-transparent bg-clip-text bg-gradient-to-r from-emerald-400 via-pink-300 to-purple-700"
        >
          Ngoding Manusiawi
        </h1>
        <h2
          class="mt-1 text-base leading-5 font-semibold text-center text-transparent bg-clip-text bg-gradient-to-r from-purple-700 via-pink-300 to-emerald-400"
        >
          Ngoding untuk <span class="underline">bermanfaat</span> bukan untuk
          <span class="italic">"mblenger"</span>.
        </h2>
      </div>
    </div>
  </div>
</template>
