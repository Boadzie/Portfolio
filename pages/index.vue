<template>
  <div>
    <section class="container py-24 cover">
      <!-- Hero head: will stick at the top -->
      <!-- Hero content: will be in the middle -->
      <div class="container py-12  has-text-centered down">
        <nav class="level">
          <div class="level-item has-text-centered">
            <div>
              <figure class="image is-128x128">
                <img class="is-rounded" src="@/assets/img/dan.jpg" />
              </figure>
            </div>
          </div>
          <div class="level-item has-text-centered">
            <div>
              <p class="buttons">
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
    <br />
    <br />
    <section class="container">
      <div class="tile is-ancestor">
        <div class="tile is-vertical is-8">
          <div class="tile">
            <div class="tile is-parent is-vertical">
              <article class="tile is-child box about">
                <h1 class="is-size-4 is-uppercase has-text-centered">
                  About Me
                </h1>
                <hr />
                <p class="is-size-5 has-text-left notification is-default">
                  <span class="has-text-success">Google certified Professional Data Analyst</span> with a passion for data and discovering insights that inform decisions.
                </p>
               
              </article>
              <!-- the skills -->
              <article class="tile is-child box">
                <h1 class="is-size-4 is-uppercase has-text-centered">Skills</h1>
                <hr />
                <br />
                <div class="columns">
                  <div class="column">
                    <p class="box has-background-success has-text-white">
                      Programming (R | Python)
                    </p>
                  </div>
                  <div class="column">
                    <p class="box has-background-dark has-text-white">
                      Database Queries
                      SQL(Postgresql)
                    </p>
                  </div>
                </div>
                <div class="columns">
                  <div class="column">
                    <p class="box has-background-info has-text-white">
                      Data Visualization
                      Tableau | R
                    </p>
                  </div>
                  <div class="column">
                    <p class="box has-background-danger has-text-white">
                     Dashboards & Reports(Rmarkdown)
                    </p>
                  </div>
                </div>
              </article>
            </div>
            <div class="tile is-parent">
              <article class="tile is-child box">
                <!-- Put any content you want -->
                <h1 class="is-size-4 is-uppercase has-text-centered">
                  Experience
                </h1>
                <hr />
                <div class="box">
                  <div class="content">
                    <p class="has-text-weight-normal">
                      <strong>Graduate -
                      <a href="https://www.ghanatechlab.com/" target="_blank"
                        >Google Data Analytics Certificate.</a
                      ></strong>
                    </p>
                    <h6
                      class="content is-small is-italic has-text-weight-normal"
                      style="margin-top: -12px"
                    >
                      April - May 2021
                    </h6>
                    <p>
                      Use R, SQL, Tableau and Excel to perform analysis and tell meaningful stories in data.
                    </p>
                    <a
                      href="https://coursera.org/share/33b0edc7b4dfb09036d7c7d91dae84d6"
                      class="button is-success is-outlined is-small is-rounded"
                      target="_blank"
                      >See it</a
                    >
                  </div>
                </div>
                <div class="box">

                  <div class="content">
                    <p class="has-text-weight-normal">
                      <strong
                        >Data scientist
                        <a href="https://www.4th-ir.com/" target="_blank"
                          >4th-IR</a
                        ></strong
                      >
                    </p>
                    <h6
                      class="content is-small is-italic has-text-weight-normal"
                      style="margin-top: -12px"
                    >
                      Since January 2020
                    </h6>
                    <p>
                      Built robust AI solutions to solve problems in Health
                      and Finance.
                    </p>
                    <a
                      href="https://www.4th-ir.com/"
                      target="_blank"
                      class="button is-success is-outlined is-small is-rounded"
                      >See it</a
                    >
                  </div>
                </div>
                <div class="box">
                  <div class="content">
                    <p class="has-text-weight-normal">
                      <strong>
                        AI Instructor/Director -
                        <a
                          href="https://www.trestleacademy.club/"
                          target="_blank"
                          >Trestle Academy Ghana(TAG)</a
                        >
                      </strong>
                    </p>
                    <h6
                      class="content is-small is-italic has-text-weight-normal"
                      style="margin-top: -12px"
                    >
                      Since July 2019
                    </h6>
                    <p>
                      Training University student to acquare skills in Data Science and AI.
                    </p>
                    <a
                      href="https://www.trestleacademy.club/"
                      target="_blank"
                      class="button is-success is-outlined is-small is-rounded"
                      >See it</a
                    >
                  </div>
                </div>
                
              </article>
            </div>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child box">
              <h1 class="is-size-4 is-uppercase has-text-centered">
                Certificates & Honors
              </h1>
              <hr />
              <br />
              <br />
              <br />
              <nav class="level">
                <div class="level-item has-text-centered">
                  <div>
                    <figure class="image is-square is-128x128">
                      
                      <img
                        class="is-square scale"
                        src="@/assets/img/google-data-analytics-certificate.png"
                      />
                    </figure>
                  </div>
                </div>
                <div class="level-item has-text-centered">
                  <div>
                    <figure class="image is-square is-128x128">
                      <img
                        class="is-square scale"
                        src="@/assets/img/analysis.jpg"
                      />
                    </figure>
                  </div>
                </div>
                <div class="level-item has-text-centered">
                  <div>
                    <figure class="image is-square is-128x128">
                      <img
                        class="is-square scale"
                        src="@/assets/img/R.jpg"
                      />
                    </figure>
                  </div>
                </div>
                <div class="level-item has-text-centered">
                  <div>
                    <figure class="image is-square is-128x128">
                      <img
                        class="is-square scale"
                        src="@/assets/img/visualization.jpg"
                      />
                    </figure>
                  </div>
                </div>
              </nav>
              <br />
              <br />
              <br />
              <nav class="level">
                <div class="level-item has-text-centered">
                  <div>
                    <figure class="image is-square is-128x128">
                      <img class="is-square scale" src="@/assets/img/process.jpg" />
                    </figure>
                  </div>
                </div>
                <div class="level-item has-text-centered">
                  <div class="level-item has-text-centered">
                    <div>
                      <figure class="image is-square is-128x128">
                        <img class="scale" src="@/assets/img/communicating-insights.png" />
                      </figure>
                    </div>
                  </div>
                </div>
                <div class="level-item has-text-centered">
                  <div>
                    <figure class="image is-square is-128x128">
                      <img class="scale" src="@/assets/img/Data Analyst.jpg" />
                    </figure>
                  </div>
                </div>
                <div class="level-item has-text-centered">
                  <div>
                    <figure class="image is-square is-128x128">
                      <img class="scale" src="@/assets/img/Gallactic.jpg" />
                    </figure>
                  </div>
                </div>
              </nav>
              <nav class="level"></nav>
            </article>
          </div>
        </div>
        <div class="tile is-parent">
          <article class="tile is-child box">
            <!-- Put any content you want -->
            <h1 class="is-size-4 is-uppercase has-text-centered">Projects</h1>
            <hr />
            <div class="card box">
              <div class="card-image">
                <figure class="image is-4by3">
                  <img
                    src="@/assets/img/website1.svg"
                    alt="Placeholder image"
                  />
                </figure>
              </div>
              <br />
              <div class="content">
                <p>
                  Trained a model to predict Titanic passenger survival rate.
                </p>
              </div>
              <a
                href="https://titanic-predictit.herokuapp.com/"
                target="_blank"
                class="button is-outlined is-small is-success is-rounded"
                >See it</a
              >
            </div>
            <div class="card box">
              <div class="card-image">
                <figure class="image is-4by3">
                  <img src="@/assets/img/blog.svg" alt="Placeholder image" />
                </figure>
              </div>
              <br />
              <div class="content">
                <p>Tech content writer for Analytics Vidhya.</p>
              </div>
              <a
                href="https://medium.com/analytics-vidhya/streamlit-the-awesome-new-way-to-deploy-data-science-machine-learning-apps-6929737b7a68"
                target="_blank"
                class="button is-outlined is-small is-success is-rounded"
                >See it</a
              >
            </div>
            <div class="card box">
              <div class="card-image">
                <figure class="image is-4by3">
                  <img src="@/assets/img/post.svg" alt="Placeholder image" />
                </figure>
              </div>
              <br />
              <div class="content">
                <p>Contribution to open source (Streamlit App Gallery).</p>
              </div>
              <a
                href="https://awesome-streamlit.org/"
                target="_blank"
                class="button is-outlined is-small is-success is-rounded"
                >See it</a
              >
            </div>
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


.nuxt-content-highlight {
  border-radius: .25rem !important;
  margin-top: 3rem;
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
  padding: 2rem;
}

.scale:hover {
  transform: scale(2.2);
}

hr {
  border: 1px solid #ea6;
  margin-top: 6px;
}
</style>
