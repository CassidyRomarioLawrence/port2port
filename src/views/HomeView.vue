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
  <div id="projects">
    <div class="container">
      <h2 class="py-2">Projects :</h2>
    </div>
    <ProjectsC/>
  </div>
</template>

<script>
import LandingC from '@/components/LandingC.vue';
import AboutC from '@/components/AboutC.vue';
import ResumeC from '@/components/ResumeC.vue';
import ProjectsC from '@/components/ProjectsC.vue';

export default {
  name: 'HomeView',
  components: {
    LandingC,
    AboutC,
    ResumeC,
    ProjectsC
  }
}
</script>

<style>
#home,#about,#resume,#projects{
  min-height: 100vh;
  scroll-margin-block: 30px;
}

#resume{
  margin-top: 20px;
}
</style>
