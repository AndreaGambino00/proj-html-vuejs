<template>
  <div id="app">
    <Header />
    <Jumbotron />
    <Courses />
    <Smart />
    <Learn />
    <Number />
    <Blogs />
    <Newsletter />
    <Footer />
  </div>
</template>

<script>
import Blogs from './components/Blogs.vue'
import Courses from './components/Courses.vue'
import Footer from './components/Footer.vue'
import Header from './components/Header.vue'
import Jumbotron from './components/Jumbotron.vue'
import Learn from './components/Learn.vue'
import Newsletter from './components/Newsletter.vue'
import Number from './components/Number.vue'
import Smart from './components/Smart.vue'

export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    Courses,
    Smart,
    Learn,
    Number,
    Blogs,
    Newsletter,
    Footer
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  
  
  
  
  
}
</style>
