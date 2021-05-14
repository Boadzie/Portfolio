<template>
  <section class="container py-24 cover">
    <!-- Hero head: will stick at the top -->
    <!-- Hero content: will be in the middle -->
    <div class="container py-12  has-text-centered down">
      <nav class="flex lg:flex-row  flex-col items-center justify-evenly">
        <div class="">
          <div>
            <figure class="image is-128x128">
              <img class="is-rounded" src="@/assets/img/dan.jpg" />
            </figure>
          </div>
        </div>
        <div class="py-4 flex justify-center items-center">
          <div>
            <p class="buttons">
              <!-- <a
                class="button mr-2 is-rounded is-small has-background-dark has-text-white"
              >
                <NuxtLink class="has-background-dark has-text-white" to="/">
                  Home
                </NuxtLink>
              </a> -->
              <!-- <a
                class="button is-rounded is-small has-background-info has-text-white"
              >
                <NuxtLink class="text-white" to="/allpost">
                  Blog
                </NuxtLink>
              </a> -->
              <a
                href="https://github.com/Boadzie"
                target="_blank"
                class="button is-rounded is-small has-background-primary has-text-white"
              >
                <span class="icon is-small">
                  <i class="fab fa-github"></i>
                </span>
                <span>GitHub</span>
              </a>
              <a
                href="https://www.linkedin.com/in/daniel-boadzie-5ab68213a/"
                target="_blank"
                class="button is-rounded is-small has-background-info has-text-white"
              >
                <span class="icon">
                  <i class="fab fa-linkedin"></i>
                </span>
                <span>Linkedin</span>
              </a>
              <a
                href="https://www.facebook.com/profile.php?id=100006259099181"
                target="_blank"
                class="button is-rounded is-small has-background-success has-text-white"
              >
                <span class="icon">
                  <i class="fab fa-facebook"></i>
                </span>
                <span>facebook</span>
              </a>
              <a
                href="https://twitter.com/boadzie"
                target="_blank"
                class="button is-rounded is-small has-background-danger has-text-white"
              >
                <span class="icon is-medium">
                  <i class="fab fa-twitter"></i>
                </span>
                <span>Twitter</span>
              </a>
              <a
                href="mailto:boadziedaniel43@gmail.com"
                subject="Want to work together"
                class="button is-rounded is-small has-background-grey has-text-white"
              >
                <span class="icon is-medium">
                  <i class="fas fa-envelope-square"></i>
                </span>
                <span>Email</span>
              </a>
              <a
                href="https://www.youracclaim.com/users/daniel-boadzie/badges"
                target="_blank"
                class="button is-rounded is-small has-background-dark has-text-white"
              >
                <span class="icon is-medium">
                  <i class="fas fa-award"></i>
                </span>
                <span>Acclaim</span>
              </a>
              <a
                href="https://docs.google.com/document/d/15Xx1ptJFRYELL3Kn20FliFn3HVyITS5_hWWQulFcLsc/edit?usp=sharing"
                target="_blank"
                class="button is-rounded is-small has-background-warning has-text-white"
              >
                <span class="icon is-medium">
                  <i class="fas fa-file"></i>
                </span>
                <span>my CV</span>
              </a>
            </p>
          </div>
        </div>
      </nav>
    </div>
  </section>
</template>
<style>
.nuxt-content-highlight {
  border-radius: 0.25rem !important;
  margin-top: 3rem;
}

.cover {
  background: #17202a;
  border-radius: 5px;
  padding: 2rem;
}

hr {
  border: 1px solid #ea6;
  margin-top: 6px;
}
</style>
