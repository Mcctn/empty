<script>
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
import Card from "./components/card.vue";
export default {
  data(){
    return{
      title:"",

      message: "This is an arg"
    }
  },
  components:{
    Card,
    Navbar,
    Hero,
  }
}

</script>

<template>
  <h1>{{message}}</h1>
  <Navbar></Navbar>
  <Hero> </Hero>


  <form>
    <h2>Please enter class title</h2>
    <input v-model="title" type="text">

    <h2>Value: {{title}}</h2>

    <button @click="handleClick">Create</button>
    <!--
    <template v-for="a in cards">
      <card v-bind:description="a.detail", v-bind:title="a.title"></card>
    </template>-->



  </form>
</template>

<style>


</style>

