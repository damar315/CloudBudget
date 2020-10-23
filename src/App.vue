<template>
  <div id="app">
    <Technology/>
    <Download/>
    <Contact/>
    <Footer/>
  </div>
</template>

<script>
import Technology from './components/Technology.vue'
import Download from './components/Download.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Technology,
    Download,
    Contact,
    Footer
  }
}
</script>

<style>
/* * {
    border: 1px solid red;
}  */
#app {
  font-family: 'Lato', sans-serif;
  /* width: 1440px;
  height: 3922px; */
  
}
</style>
