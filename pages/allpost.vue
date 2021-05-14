<template>
  <section class="container py-4 mx-auto ">
    <div class="py-14 cover mb-4 has-text-center has-text-white">
      <h1 class="text-5xl text-center py-4">Blog Posts</h1>
      <ul class="w-full py-4 mr-auto ml-auto px-2 lg:px-0 lg:w-5/6">
        <li v-for="article of articles" :key="article.slug">
          <div class="py-6">
             <NuxtLink :to="{ name: 'blog-slug', params: { slug: article.slug } }">
              <h2 class="hover:text-blue-500 text-4xl text-white lg:text-left text-center">
                {{ article.title }}
              </h2>
            </NuxtLink>
            <h3 class="text-sm lg:text-left text-center">
              {{ article.description }}
            </h3>
          </div>
          <img
            class="w-full h-96 rounded-lg object-center object-cover mt-3 mb-3"
            :src="article.img"
          />
        </li>
      </ul>
    </div>
  </section>
</template>

<script>
export default {
  async asyncData({ $content, params }) {
    const articles = await $content("articles")
      .only(["title", "description", "img", "slug"])
      .sortBy("createdAt", "asc")
      .fetch();

    return {
      articles
    };
  }
};
</script>
