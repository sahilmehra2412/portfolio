<template>
  <div>
    <Navbar/>
    <Hero/>
    <About/>
    <Projects/>
    <Contact/>
  </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
import Hero from '../components/Hero.vue';
import Contact from '../components/Contact.vue';
import Projects from '../components/Projects.vue';

export default {
    name: "IndexPage",
    components: { Navbar, Hero, Contact, Projects }
}
</script>

<style>
  html {
    scroll-behavior: smooth;
  }
</style>