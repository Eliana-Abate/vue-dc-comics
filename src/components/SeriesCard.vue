<template>
  <section class="card">
      
    <img :id="`img${index}`" :src="film.thumb" :alt="film.series">
    <p>{{film.series}}</p>
  </section>
</template>

<script>
export default {
    name: "SeriesCard",
    props: ['film', 'index']

}
</script>

<style lang="scss" scoped>
    .card {
        flex-basis: calc(100% / 6 - 20px);
        height: 300px;
        font-family: sans-serif;
        font-size: 0.8em;
        color: white;
        text-transform: uppercase;
        margin: 0px 10px;

        img {
            width: 100%;
            height: 59%;
            object-fit: cover;
            object-position: top;
        }
    }
</style>