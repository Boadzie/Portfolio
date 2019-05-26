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
                <a class="button is-rounded is-small has-background-dark has-text-white">
                  <span class="icon is-medium">
                    <i class="fas fa-envelope-square"></i>
                  </span>
                  <span>Acclaim</span>
                </a>
                <a class="button is-rounded is-small has-background-warning has-text-white">
                  <span class="icon is-medium">
                    <i class="fas fa-book"></i>
                  </span>
                  <span>Blog</span>
                </a>
              </p>
            </div>
          </div>
        </nav>
      </div>
    </section>
    <br>
    <br>
    <section class="container">
      <div class="tile is-ancestor">
        <div class="tile is-vertical is-8">
          <div class="tile">
            <div class="tile is-parent is-vertical">
              <article class="tile is-child box about">
                <h1 class="is-size-4 is-uppercase has-text-centered">About Me</h1>
                <hr>
                <p class="has-text-left notification">
                  I'm an
                  <strong class="title is-6">IBM certified and passionate</strong>
                  <strong class="title is-4">Data scientist, AI Engineer and a Full-stack Developer</strong> with
                  <strong class="title is-4">3 years</strong> of experience.
                </p>
                <br>
                <blockquote
                  class="notification has-text-grey is-italic has-text-left"
                >I look forward to working with you soon!</blockquote>
              </article>
              <!-- the skills -->
              <article class="tile is-child box">
                <h1 class="is-size-4 is-uppercase has-text-centered">Skills</h1>
                <hr>
                <br>
                <div class="columns">
                  <div class="column">
                    <p class="box has-background-success has-text-white">Data Science (Python | R)</p>
                  </div>
                  <div class="column">
                    <p class="box has-background-dark has-text-white">Artificial Intelligence</p>
                  </div>
                </div>
                <div class="columns">
                  <div class="column">
                    <p class="box has-background-info has-text-white">VENoM-Stack (Vue.js)</p>
                  </div>
                  <div class="column">
                    <p class="box has-background-danger has-text-white">DevOps (Git, Docker, AWS)</p>
                  </div>
                </div>
              </article>
            </div>
            <div class="tile is-parent">
              <article class="tile is-child box">
                <!-- Put any content you want -->
                <h1 class="is-size-4 is-uppercase has-text-centered">Experience</h1>
                <hr>
                <div class="box">
                  <div class="content">
                    <p class="has-text-weight-normal">
                      <strong>AI/Data Science Instructor</strong> - Digital Youth Africa | University of Ghana Ethical AI Club
                    </p>
                    <h6
                      class="content is-small is-italic has-text-weight-normal"
                      style=" margin-top:-12px;"
                    >Since February 2019</h6>
                    <p>Helping students master the new technologies</p>
                  </div>
                </div>
                <div class="box">
                  <div class="content">
                    <p class="has-text-weight-normal">
                      <strong>Project Manager and Content Writer</strong> - Ivocate
                    </p>
                    <h6
                      class="content is-small is-italic has-text-weight-normal"
                      style=" margin-top:-12px;"
                    >June 2018 to January 2019</h6>
                    <p>Led my team to build a platform that helps victims of gender-based violence</p>
                    <a
                      href="http://ivocate.org/"
                      target="_blank"
                      class="button is-success is-outlined is-small is-rounded"
                    >See it</a>
                  </div>
                </div>
                <div class="box">
                  <div class="content">
                    <p class="has-text-weight-normal">
                      <strong>Workshop Coordinator(Volunteer)</strong> - GhScientific
                    </p>
                    <h6
                      class="content is-small is-italic has-text-weight-normal"
                      style=" margin-top:-12px;"
                    >Since December 2015</h6>
                    <p>Helping to conduct and coordinate successful STEM related events</p>
                    <a
                      href="https://ghscientific.com/"
                      class="button is-success is-outlined is-small is-rounded"
                      target="_blank"
                    >See it</a>
                  </div>
                </div>
              </article>
            </div>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child box">
              <h1 class="is-size-4 is-uppercase has-text-centered">Certificates & Honors</h1>
              <hr>
              <nav class="level">
                <div class="level-item has-text-centered">
                  <div>
                    <figure class="image is-128x128">
                      <img class="is-rounded" src="@/assets/img/artificial-intelligence-v2.png">
                    </figure>
                  </div>
                </div>
                <div class="level-item has-text-centered">
                  <div>
                    <figure class="image is-128x128">
                      <img class="is-rounded" src="@/assets/img/data-science-fundamentals.png">
                    </figure>
                  </div>
                </div>
                <div class="level-item has-text-centered">
                  <div>
                    <figure class="image is-128x128">
                      <img class="is-rounded" src="@/assets/img/communicating-insights.png">
                    </figure>
                  </div>
                </div>
                <div class="level-item has-text-centered">
                  <div>
                    <figure class="image is-128x128">
                      <img class="is-rounded" src="@/assets/img/natural-language-processing-v2.png">
                    </figure>
                  </div>
                </div>
              </nav>
              <nav class="level">
                <div class="level-item has-text-centered">
                  <div>
                    <figure class="image is-128x128">
                      <img class="is-rounded" src="@/assets/img/chatbot.png">
                    </figure>
                  </div>
                </div>
                <div class="level-item has-text-centered">
                  <div>
                    <figure class="image is-128x128">
                      <img class="is-rounded" src="@/assets/img/api.png">
                    </figure>
                  </div>
                </div>
                <div class="level-item has-text-centered">
                  <div>
                    <figure class="image is-square is-128x128">
                      <img class src="@/assets/img/Data Analyst.jpg">
                    </figure>
                  </div>
                </div>
                <div class="level-item has-text-centered">
                  <div>
                    <figure class="image is-square is-128x128">
                      <img class src="@/assets/img/Gallactic.jpg">
                    </figure>
                  </div>
                </div>
              </nav>
            </article>
          </div>
        </div>
        <div class="tile is-parent">
          <article class="tile is-child box">
            <!-- Put any content you want -->
            <h1 class="is-size-4 is-uppercase has-text-centered">Projects</h1>
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

.image {
  width: 100%;
  height: 120px;
}

img {
  width: 1em;
  height: 30px;
}

.cover {
  background: #17202a;
  border-radius: 5px;
}

hr {
  border: 1px solid #ea6;
  margin-top: 6px;
}
</style>
