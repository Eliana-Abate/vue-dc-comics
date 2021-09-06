<template>
  <div id="app">
    <Header/>
    <main>
        <Hero/>
        <Utilities/>
    </main>
    <footer>
      <Footer/>
    </footer>

    
    
   
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Hero from '@/components/Hero.vue';
import Utilities from '@/components/Utilities.vue';
import Footer from '@/components/Footer.vue';


export default {
  name: 'App',
  components: {
    Header,
    Hero,
    Utilities,
    Footer,
    
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
    font-family: 'Open Sans Condensed', sans-serif;
  }

 


  //UTILITIES
  .container {
    max-width: 1200px;
    margin: auto;
  }

  .row {
        display: flex;
        align-items: center;
    }

  .col-20 {
        flex-basis: calc(100% * 20 / 100);
    }

  .col-40 {
        flex-basis: calc(100% * 40 / 100);
    }
  
  .col-50 {
        flex-basis: calc(100% * 50 / 100);
    }

  .col-60 {
        flex-basis: calc(100% * 60 / 100);
    }
  
  .h-100 {
    height: 100%;
  }

 
</style>
