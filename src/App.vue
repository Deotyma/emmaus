<template>
  <div id="app">
   <NavBar/>
   <SliderFirst/>

    <router-view/>
  </div>
</template>

<script>
  import NavBar from '@/components/NavBar.vue'
  import SliderFirst from '@/components/SliderFirst.vue'
    
  export default {
    components: {
      NavBar,
      SliderFirst
    }
  }
</script>

<style>
</style>
