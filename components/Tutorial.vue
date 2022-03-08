<!-- Please remove this file from your project -->
<template>
  <div
    class="
      relative
      flex
      items-top
      justify-center
      min-h-screen
      bg-gray-100
      sm:items-center sm:pt-0
    "
  >
    <link
      href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css"
      rel="stylesheet"
    />
    <div class="max-w-4xl mx-auto sm:px-6 lg:px-8">
      <a
        class="flex justify-center pt-8 sm:pt-0"
        href="https://nuxtjs.org"
        target="_blank"
      >
        <svg
          width="218"
          height="45"
          viewBox="0 0 159 30"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        ></svg>
      </a>
      <div class="mt-8 bg-white overflow-hidden shadow sm:rounded-lg p-6">
        <h2 class="text-2xl leading-7 font-semibold">
          Welcome to your Nuxt Application
        </h2>
        <p class="mt-3 text-gray-600">
          We recommend you take a look at the
          <a
            href="https://nuxtjs.org"
            target="_blank"
            class="button--doc text-green-500 hover:underline"
            >Nuxt documentation</a
          >, whether you are new or have previous experience with the
          framework.<br />
        </p>
        <p class="mt-4 pt-4 text-gray-800 border-t border-dashed">
          To get started, remove
          <code class="bg-gray-100 text-sm p-1 rounded border"
            >components/Tutorial.vue</code
          >
          and start coding in
          <code class="bg-gray-100 text-sm p-1 rounded border"
            >pages/index.vue</code
          >. Have fun!
        </p>
      </div>
      <div class="flex justify-center pt-4 space-x-2">
        <a href="https://github.com/nuxt/nuxt.js" target="_blank"
          ><svg
            class="w-6 h-6 text-gray-600 hover:text-gray-800 button--github"
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            aria-hidden="true"
            role="img"
            width="32"
            height="32"
            preserveAspectRatio="xMidYMid meet"
            viewBox="0 0 24 24"
          ></svg
        ></a>
        <a href="https://twitter.com/nuxt_js" target="_blank"
          ><svg
            class="w-6 h-6 text-gray-600 hover:text-gray-800"
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            aria-hidden="true"
            role="img"
            width="32"
            height="32"
            preserveAspectRatio="xMidYMid meet"
            viewBox="0 0 24 24"
          ></svg
        ></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NuxtTutorial',
};
</script>
