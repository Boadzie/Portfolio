<template>
  <section class="container mx-auto px-2  ">
    <!-- <nav>
      <ul>
        <li v-for="link of article.toc" :key="link.id">
          <NuxtLink  :to="`#${link.id}`">{{ link.text }}</NuxtLink>
        </li>
      </ul>
    </nav> -->

    <div class="py-14 cover mb-4 has-text-center has-text-white">
      <article class="w-full mr-auto ml-auto px-2 lg:px-0 lg:w-5/6">
        <h1 class="text-5xl text-teal-400">{{ article.title }}</h1>
        <small class="text-sm">Article last updated: {{ formatDate(article.updatedAt) }}</small>
        <img class="w-full max-h-96 rounded-lg object-center object-cover mt-3 mb-3" :src="article.img" :alt="article.alt" />

        <nuxt-content :document="article" />
      </article>
    </div>
  </section>
</template>

<script>
export default {
  async asyncData({ $content, params }) {
    const article = await $content("articles", params.slug).fetch();

    return { article };
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

.nuxt-content-highlight{
  padding: 10px;
  border-radius: 0.25rem;
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
