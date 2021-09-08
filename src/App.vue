<template>
  <div id="app">
    <header>
      <DcWorld/>
      <Header/>
    </header>
    <main>
        <Hero/>
        <Series/>
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
import Series from '@/components/Series.vue';
import Utilities from '@/components/Utilities.vue';
import Footer from '@/components/Footer.vue';
import Social from '@/components/Social.vue';


export default {
  name: 'App',
  components: {
    DcWorld,
    Header,
    Hero,
    Series,
    Utilities,
    Footer,
    Social,
    
  }

}
</script>

<style lang="scss">
  @import "@/assets/scss/style.scss";
</style>
