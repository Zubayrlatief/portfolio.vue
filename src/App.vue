<template>
  <NavBar/>
  <HomePage/>
  <AboutMe/>
  <MyProjects/>
  <MyResume/>
  <MyTestimonials/>
  <ContactMe/>
  <router-view/>
  <AllFooter/>
</template>

<script>
import AllFooter from './components/AllFooter.vue';
import NavBar from './components/NavBar.vue';
import HomePage from './components/HomePage.vue';
import AboutMe from './components/AboutMe.vue';
import MyProjects from './components/MyProjects.vue';
import MyResume from './components/MyResume.vue';
import MyTestimonials from './components/MyTestimonials.vue';
import ContactMe from './components/ContactMe.vue';

export default {
  components: {
    NavBar,
    AllFooter,
    HomePage,
    AboutMe,
    MyProjects,
    MyResume,
    MyTestimonials,
    ContactMe,
  }
}

</script>
<style>
  
</style>