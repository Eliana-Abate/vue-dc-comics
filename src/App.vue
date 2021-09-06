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
  margin: 0;
  box-sizing: border-box;
  background-color: #000;
  height: 100vh;
  padding: 30px 0;
}

.container {
  max-width: 1200px;
  margin: auto;
}
</style>
