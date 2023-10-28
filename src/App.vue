<template>
  <Navbar/> 
  <Presentation/>
  <Projects/>
  <Info/>
  <Footer/>
</template>

<script>
import Footer from './components/Footer.vue';
import Presentation from './components/Presentation.vue';
import Navbar from './components/Navbar.vue';
import Projects from './components/Projects.vue';
import Info from './components/Info.vue';

export default {
    components: { Navbar, Presentation, Projects, Info, Footer }
}
</script>

<style>

</style>