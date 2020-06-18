<template>
  <div id="app">
    <Hero msg="Hello World.  Lorem ipsum" title="Welcome to Your Vue.js App using Buefy!"/>
    <contact title="Contact Us" />
  </div>
</template>

<script>
import Hero from './components/Hero.vue'
import Contact from './components/Contact.vue'

export default {
  name: 'App',
  components: {
    Hero,
    Contact
  }
}
</script>

<style>
</style>
