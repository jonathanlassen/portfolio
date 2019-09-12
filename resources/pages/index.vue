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
          <div class="bio">
            Hello! I'm Jonathan Lassen and I'm hitching myself to this crazy
            thing called the internet. I have experience on the back-end, but
            have fallen for the fun and responsiveness of front-end frameworks.
            I'm seeking the learning that will come from working in a team on
            larger projects. Also, I speak and read Chinese, and
            love to try foods I've never had before.
          </div>
          <div class="links">
            <a
              href="https://www.linkedin.com/in/jonathan-lassen-1b018317a/"
              target="_blank"
              class="button--grey"
            >LinkedIn</a>
            <a href="https://github.com/jonathanlassen" target="_blank" class="button--grey">GitHub</a>
            <a href="jonathan.lassen@gmail.com" target="_blank" class="button--grey">Email</a>
          </div>
        </div>
        <div class="lg:w-2/5 sm:w-full p-2">
          <h1 class="selectedprojects">Selected Projects</h1>

          <h1 class="title3">Find a Framer</h1>
          <div class="projecttext">Simple API-driven bookmarks application using jQuery.</div>
          <h2 class="subtitle">
            <img class="imagefilter" src="~/assets/leafscreen.png" />
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

          <h1 class="title3">Bookmarks</h1>
          <div class="projecttext">Simple API-driven bookmarks application using jQuery.</div>
          <h2 class="subtitle">
            <img class="imagefilter" src="~/assets/bookmarks.png" />
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
  @apply flex justify-center items-center text-center mx-auto max-w-full min-h-screen flex-row flex-wrap;
}
.container2 {
  background-color: hsla(40, 4%, 14%, 0.98);
  @apply min-h-screen;
}

.title {
  @apply font-sans;
  font-size: 50px;
  color: #9fa8a3;
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
  border-bottom: 1px solid #444;
  padding: 10px;
}

.title3 {
  @apply font-sans;
  font-size: 20px;
  color: #9fa8a3;
  margin-top: 15px;
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
  paddding-right: 80px;
}

.imagefilter {
  filter: contrast(80%);
  filter: drop-shadow(8px 8px 10px rgba(0, 0, 0, 0.9));
  border-radius: 10px;
  margin: 20px;
}

.links {
  padding-top: 15px;
}
</style>
