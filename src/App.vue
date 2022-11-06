<template>
  <div id="app">
    <NavBar/>
    <Section/>
    <Project/>
    <About/>
    <Footer/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Section from './components/Section.vue'
import Project from './components/Projects.vue'
import About from './components/About.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Section,
    Project,
    About,
    Footer,
  }
}
</script>

<style>
*{
    font-family: Arial, Helvetica, sans-serif;
}
</style>
