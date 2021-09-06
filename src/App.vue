<template>
  <div id="app">
    <Header/>
    
   
  </div>
</template>

<script>
import Header from '@/components/Header.vue'


export default {
  name: 'App',
  components: {
    Header,
    
  }
}
</script>

<style lang="scss">
body {
  background-color: #000;
  height: 100vh;
}
</style>
