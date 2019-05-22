<template>
  <div>
    <section class="card container cover">
      <!-- Hero head: will stick at the top -->
      <!-- Hero content: will be in the middle -->
      <div class="container has-text-centered down">
        <nav class="level">
          <div class="level-item has-text-centered">
            <div>
              <figure class="image is-128x128">
                <img class="is-rounded" src="@/assets/img/dan.jpg">
              </figure>
            </div>
          </div>
          <div class="level-item has-text-centered">
            <div>
              <p class="buttons">
                <a class="button is-rounded is-small has-background-primary has-text-white">
                  <span class="icon is-small">
                    <i class="fab fa-github"></i>
                  </span>
                  <span>GitHub</span>
                </a>
                <a class="button is-rounded is-small has-background-info has-text-white">
                  <span class="icon">
                    <i class="fab fa-linkedin"></i>
                  </span>
                  <span>Linkedin</span>
                </a>
                <a class="button is-rounded is-small has-background-success has-text-white">
                  <span class="icon">
                    <i class="fab fa-facebook"></i>
                  </span>
                  <span>facebook</span>
                </a>
                <a class="button is-rounded is-small has-background-danger has-text-white">
                  <span class="icon is-medium">
                    <i class="fab fa-twitter"></i>
                  </span>
                  <span>Twitter</span>
                </a>
                <a class="button is-rounded is-small has-background-grey has-text-white">
                  <span class="icon is-medium">
                    <i class="fas fa-envelope-square"></i>
                  </span>
                  <span>Email</span>
                </a>
              </p>
            </div>
          </div>
        </nav>
      </div>
    </section>
    <br>
    <br>
    <section class="container has-text-centered">
      <div class="tile is-ancestor">
        <div class="tile is-vertical is-8">
          <div class="tile">
            <div class="tile is-parent is-vertical">
              <article class="tile is-child box about">
                <h1 class="is-size-4 is-uppercase">About Me</h1>
                <hr>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore ratione nesciunt accusantium
                  laborum, suscipit ut molestias iusto odio molestiae.</p>
              </article>
              <!-- the skills -->
              <article class="tile is-child box">
                <h1 class="is-size-4 is-uppercase">Skills</h1>
                <hr>
                <div class="progress-wrapper">
                  <progress class="progress is-danger is-large" value="81" max="100">90%</progress>
                  <p class="progress-value has-text-white">VENoM-Stack(Vue.js)</p>
                </div>
                <div class="progress-wrapper">
                  <progress class="progress is-primary is-large" value="79" max="100">90%</progress>
                  <p class="progress-value has-text-white">Data Science</p>
                </div>
                <div class="progress-wrapper">
                  <progress class="progress is-grey is-large" value="75" max="100">90%</progress>
                  <p class="progress-value has-text-white">Artificial Intelligence</p>
                </div>
                <div class="progress-wrapper">
                  <progress class="progress is-info is-large" value="78" max="100">90%</progress>
                  <p class="progress-value has-text-white">DevOps</p>
                </div>
              </article>
            </div>
            <div class="tile is-parent">
              <article class="tile is-child box">
                <!-- Put any content you want -->
                <h1 class="is-size-4 is-uppercase">Experience</h1>
                <hr>
              </article>
            </div>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child box">
              <h1 class="is-size-4 is-uppercase">Certificates & Honors</h1>
              <hr>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Explicabo esse facilis provident, incidunt
              sed qui totam atque dicta illo! Cumque labore laudantium odio, blanditiis ipsa minima nobis eius totam
              minus amet, fugit dolore placeat delectus dolorum? Odio mollitia culpa totam?
            </article>
          </div>
        </div>
        <div class="tile is-parent">
          <article class="tile is-child box">
            <!-- Put any content you want -->
            <h1 class="is-size-4 is-uppercase">Projects</h1>
            <hr>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iste, doloribus.</p>
          </article>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
  export default {
    components: {}
  };

</script>

<style>
  .down {
    margin-bottom: em !important;
  }

  .card {
    padding: 1em;
    margin-top: 1em !important;
  }

  img {
    width: 1em;
    height: 30px;
  }

  .cover {
    background: #17202a;
    border-radius: 5px;
  }

  .progress-wrapper {
    position: relative;
  }

  .progress-value {
    position: absolute;
    top: 0;
    left: 50%;
    transform: translateX(-50%);
    font-size: calc(1rem / 1.5);
    line-height: 1rem;
    font-weight: bold;
  }

  .progress.is-small+.progress-value {
    font-size: calc(0.75rem / 1.5);
    line-height: 0.75rem;
  }

  .progress.is-medium+.progress-value {
    font-size: calc(1.25rem / 1.5);
    line-height: 1.25rem;
  }

  .progress.is-large+.progress-value {
    font-size: calc(1.5rem / 1.5);
    line-height: 1.5rem;
  }

  hr {
    border: 1px solid #ea6;
    margin-top: 6px;
  }

</style>
