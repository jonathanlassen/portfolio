<template>
  <section
    class="min-h-screen bg-cover bg-center"
    style="background-image: url('https://images.unsplash.com/photo-1461749280684-dccba630e2f6?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80')"
  >
    <div class="container2">
      <div class="container">
        <link href="https://fonts.googleapis.com/css?family=Montserrat" />
        <link href="https://fonts.googleapis.com/css?family=Cardo" />
        <div class="lg:w-1/5 sm:w-full p-2">
          <h1 class="title">Jonathan Lassen</h1>
          <div
            class="bio"
          >I'm Jonathan Lassen, a full stack developer. I've been developing web applications on the side for years, and have enjoyed it so much I'm now doing it full time. I will admit the constant learning is a complete high for me. I've fallen in love with the responsiveness and order that modern front-end JS frameworks provide (React and Vue are the ones I know best), and am comfortable in the back-end in a number of languages. I am excited to continue to learn and grow on a larger team. Check out my projects, or get in touch! Other than coding, my interests include: traveling (I spent nearly a decade in China and am fluent in Mandarin), exploring new foods, and busting my brain in no-luck modern boardgames.</div>
          <div class="links">
            <a
              href="https://www.linkedin.com/in/jonathan-lassen/"
              target="_blank"
              class="button--grey"
            >LinkedIn</a>
            <a href="https://github.com/jonathanlassen" target="_blank" class="button--grey">GitHub</a>
            <a href="mailto: jonathan.lassen@gmail.com" target="_blank" class="button--grey">Email</a>
          </div>
        </div>
        <div class="lg:w-2/5 sm:w-full p-2">
          <h1 class="selectedprojects">Selected Projects</h1>

          <h1 class="title3">Find a Framer</h1>
          <div
            class="projecttext"
          >Tool for customers to find frame shops, and frame shops to market to potential customers. React, Nodejs, Express, PostgreSql, Knex.</div>
          <h2 class="subtitle">
            <img
              class="imagefilter"
              src="~/assets/matcher.jpg"
              alt="find a framer application screenshot"
            />
          </h2>
          <div class="links">
            <a
              href="https://github.com/jonathanlassen/react-leaf"
              target="_blank"
              class="button--grey"
            >GitHub</a>
            <a
              href="https://react-leaf.jonathanlassen.now.sh/"
              target="_blank"
              class="button--grey"
            >Live</a>
          </div>

          <h1 class="title3">Mat Matcher</h1>
          <div
            class="projecttext"
          >Innovative tool for picture framers to match mat colors across vendors, and find the closest color match by hex color. Vue, Mysql, Laravel.</div>
          <h2 class="subtitle">
            <img
              class="imagefilter"
              src="~/assets/matscreen.png"
              alt="mat matching application screenshot"
            />
          </h2>
          <div class="links">
            <a
              href="https://pictureframedesigns.com/matmatcher"
              target="_blank"
              class="button--grey"
            >Live</a>
          </div>

          <h1 class="title3">YTDB</h1>
          <div
            class="projecttext"
          >IMDb for youtube channels. Search our db or Youtube's db for channels by name, topic or keyword. Rate and review them. Add your favorite channels to your dashboard. React, Nodejs, Express, PostgreSql, Cypress.</div>
          <h2 class="subtitle">
            <img
              class="imagefilter"
              src="~/assets/ytdbscreen.png"
              alt="YTDB application screenshot"
            />
          </h2>
          <div class="links">
            <a
              href="https://github.com/thinkful-ei-cheetah/YTDB-Client"
              target="_blank"
              class="button--grey"
            >GitHub</a>
            <a
              href="https://ytdb-client.jonathanlassen.now.sh/"
              target="_blank"
              class="button--grey"
            >Live</a>
          </div>

          <h1 class="title3">Bookmarks</h1>
          <div
            class="projecttext"
          >Simple API-driven bookmarks application using jQuery / HTML / CSS.</div>
          <h2 class="subtitle">
            <img
              class="imagefilter"
              src="~/assets/bookmarks.png"
              alt="bookmarks application screenshot"
            />
          </h2>
          <div class="links">
            <a
              href="https://github.com/jonathanlassen/bookmarkts"
              target="_blank"
              class="button--grey"
            >GitHub</a>
            <a
              href="https://jonathanlassen.github.io/bookmarkts/"
              target="_blank"
              class="button--grey"
            >Live</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  components: {}
}
</script>

<style>
.container {
  @apply flex justify-center items-start text-center mx-auto max-w-full min-h-screen flex-row flex-wrap;
}
.container2 {
  background-color: hsla(40, 4%, 14%, 0.98);
  @apply min-h-screen;
}

.title {
  @apply font-sans;
  font-size: 50px;
  color: #9fa8a3;
  padding-top: 25px;
  padding-right: 10px;
  padding-left: 10px;
}

.title2 {
  @apply font-sans;
  font-size: 30px;
  color: #9fa8a3;
}

.selectedprojects {
  @apply font-sans;
  font-size: 30px;
  color: #9fa8a3;
  padding-top: 25px;
}

.title3 {
  @apply font-sans;
  font-size: 20px;
  color: #9fa8a3;
  margin-top: 10px;
  padding-top: 10px;
  border-top: 1px solid #444;
}

.subtitle {
  font-family: 'Cardo';
  font-weight: 200;
  font-size: 24px;
  color: #e3e0cf;
  word-spacing: 5px;
  margin-top: 15px;
}

.bio {
  font-family: 'Cardo';
  font-size: 18px;
  color: #e3e0cf;
  margin-top: 15px;
  text-align: left;
  padding-left: 20px;
  padding-right: 20px;
  @apply leading-normal;
}

.projecttext {
  font-family: 'Cardo';
  font-size: 16px;
  color: #e3e0cf;
  margin-top: 20px;
  text-align: left;
  @apply leading-normal;
  padding-left: 80px;
  padding-right: 80px;
}

.imagefilter {
  filter: contrast(80%);
  border-radius: 20px;
  padding-left: 10px;
  padding-right: 10px;
}

.links {
  padding-top: 5px;
  padding-bottom: 5px;
}

a {
  padding: 0;
  margin: 0;
}
</style>
