<template>
  <section class="container py-4 mx-auto px-2  ">
    <div class="py-14 cover mb-4 has-text-center has-text-white">
      <article class="w-full py-4 mr-auto ml-auto px-2 lg:px-0 lg:w-5/6">
        <h1 class="text-5xl text-teal-400 lg:text-left text-center">
          {{ article.title }}
        </h1>
        <small class="text-sm lg:text-left text-center"
          >Article last updated: {{ formatDate(article.updatedAt) }}</small
        >
        <img
          class="mt-4 mb-4 w-full h-96 rounded-lg object-center object-cover mt-3 mb-3"
          :src="article.img"
          :alt="article.alt"
        />

        <nuxt-content :document="article" />
        <prev-next :prev="prev" :next="next" />
      </article>
    </div>
  </section>
</template>

<script>
export default {
  async asyncData({ $content, params }) {
    const article = await $content("articles", params.slug).fetch();

    const [prev, next] = await $content("articles")
      .only(["title", "slug"])
      .sortBy("createdAt", "asc")
      .surround(params.slug)
      .fetch();

    return {
      article,
      prev,
      next
    };
  },

  methods: {
    formatDate(date) {
      const options = { year: "numeric", month: "long", day: "numeric" };
      return new Date(date).toLocaleDateString("en", options);
    }
  }
};
</script>
<style>
.nuxt-content-highlight {
  padding: 10px;
  border-radius: 0.25rem;
}

.nuxt-content img {
  width: 100%;
  max-height: 23rem;
}

.cover {
  background: #17202a;
  border-radius: 5px;
}

.nuxt-content h2 {
  margin-left: -22px;
  margin-bottom: 5px;
  font-weight: bold;
  font-size: 34px;
}

.nuxt-content p {
  margin-bottom: 6px;
  font-size: 20px;
}
</style>
