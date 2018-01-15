<template>
  <div id="app">
    <Navbar/>
    <section>
      <router-view/>
    </section>
  </div>
</template>

<script>
import Navbar from "./components/Navbar"
export default {
  name: 'App',
  components:{
      Navbar
  }
}
</script>

<style>
 
</style>
