<template>
  <div id="app">
    <header>
      <DcWorld/>
      <Header/>
    </header>
    <main>
        <Hero/>
        <Utilities/>
    </main>
    <footer>
      <Footer/>
      <Social/>
    </footer>

    
    
   
  </div>
</template>

<script>
import DcWorld from '@/components/DcWorld.vue';
import Header from '@/components/Header.vue';
import Hero from '@/components/Hero.vue';
import Utilities from '@/components/Utilities.vue';
import Footer from '@/components/Footer.vue';
import Social from '@/components/Social.vue';


export default {
  name: 'App',
  components: {
    DcWorld,
    Header,
    Hero,
    Utilities,
    Footer,
    Social,
    
  }
}
</script>

<style lang="scss">
  body {
    margin: 0;
    box-sizing: border-box;
    background-color: #000;
    height: 100vh;
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

  .clickable {
    cursor: pointer;
  }

 
</style>
