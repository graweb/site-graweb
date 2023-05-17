<template>
  <div>
    <section class="container mx-auto">
      <h1
        class="ml-6 my-4 text-2xl md:text-4xl text-blue-800 font-bold leading-tight text-center md:text-left slide-in-bottom-h1"
      >
        Projects
      </h1>

      <div
        v-if="$fetchState.pending"
        class="flex items-center justify-center min-h-screen"
      >
        <span
          class="bg-indigo-400 h-max w-max rounded-lg text-white font-bold hover:bg-indigo-300 hover:cursor-not-allowed duration-[500ms,800ms]"
        >
          <div class="flex items-center justify-center m-[10px]">
            <div
              class="h-5 w-5 border-t-transparent border-solid animate-spin rounded-full border-white border-4"
            ></div>
            <div class="ml-2">Processing...</div>
          </div>
        </span>
      </div>

      <div
        v-else
        class="grid justify-center md:grid-cols-2 lg:grid-cols-4 gap-5 lg:gap-5 my-10"
      >
        <div
          class="bg-white font-semibold text-center rounded-3xl border shadow-lg p-10 max-w-xs"
          v-for="repo in repos"
          :key="repo.id"
        >
          <h1 class="text-lg text-gray-700 my-4">{{ repo.name }}</h1>
          <p class="text-xs text-gray-400 my-4">{{ repo.description }}</p>
          <a
            :href="repo.html_url"
            target="_blank"
            class="bg-gray-600 px-8 py-2 rounded-3xl text-gray-100 font-semibold uppercase tracking-wide"
          >
            Visit
          </a>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {
      repos: [],
    };
  },

  async fetch() {
    this.repos = await this.$axios.$get(
      "https://api.github.com/users/graweb/repos"
    );
  },
};
</script>

<style>
</style>
