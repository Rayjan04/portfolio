<template>
  <div id="app">
    <NavBar/>
    <Section/>
    <Project/>
    <About/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Section from './components/Section.vue'
import Project from './components/Projects.vue'
import About from './components/About.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Section,
    Project,
    About,
  }
}
</script>

<style>
*{
    font-family: Arial, Helvetica, sans-serif;
}
</style>
