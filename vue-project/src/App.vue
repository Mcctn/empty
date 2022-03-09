<script>
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
export default {
  data(){
    return{
      message: "This is an arg"
    }
  },
  components:{
    Navbar,
    Hero,
  }
}

</script>

<template>
  <h1>{{message}}</h1>
  <Navbar></Navbar>
  <Hero> </Hero>
</template>

<style>


</style>

