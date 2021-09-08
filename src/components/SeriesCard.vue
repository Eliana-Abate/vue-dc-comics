<template>
  <section class="card">
      
    <img :src="film.thumb" :alt="film.series">
    <p>{{film.series}}</p>

  </section>
</template>

<script>
export default {
    name: "SeriesCard",
    props: ['film']

}
</script>

<style lang="scss" scoped>
    .card {
        flex-basis: calc(100% / 6);
        font-family: sans-serif;
        color: white;
        text-transform: uppercase;
        background-color: yellow ;
    }

   

    
    

</style>