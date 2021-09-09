<template>
  <div class="portfolio">
      <home />
      <about />
      <project />
      <contact />
  </div>
</template>

<script>
import Home from '../components/Home-section/Home.vue';
import Project from '../components/Project/Project.vue';
import About from '../components/About/About.vue';
import Contact from '../components/Contact/Contact.vue';
export default {
  components: { 
      Home,
      Project,
      About,
      Contact,
    }, 

}
</script>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.portfolio {
    background-color: #222222;
    width: 1440px;
    margin: auto;
    overflow: hidden;
    overflow-x: hidden;
}

.mt-1 {
  margin-top: 1rem;
}

.container {
  width: 70%;
  margin: auto;
}
@media screen and (max-width: 1440px) {
  .portfolio {
    /* width: 1429px; */
    width: 100vw;
  }
}
</style>