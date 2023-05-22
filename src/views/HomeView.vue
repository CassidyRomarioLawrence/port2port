<template>
  <div id="home">
    <LandingC/>
  </div>
  <div id="about">
    <div class="container">
      <h2 class="py-2">About Me :</h2>
    </div>
    <AboutC/>
  </div>
  <div id="resume">
    <div class="container">
      <h2 class="py-2">Resume :</h2>
    </div>
    <ResumeC/>
  </div>
</template>

<script>
import LandingC from '@/components/LandingC.vue';
import AboutC from '@/components/AboutC.vue';
import ResumeC from '@/components/ResumeC.vue';

export default {
  name: 'HomeView',
  components: {
    LandingC,
    AboutC,
    ResumeC
  }
}
</script>

<style>
#home,#about,#resume{
  min-height: 100vh;
}
</style>
