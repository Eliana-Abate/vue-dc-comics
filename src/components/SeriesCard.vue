<template>
  <section class="card">
      <img src="" alt="">
      <h5>{{film.series}}</h5>

  </section>
</template>

<script>
export default {
    name: "SeriesCard",
    props: ['film']

}
</script>

<style>
    .card {
        flex-basis: calc(100% / 6);
        color: white;
        text-transform: uppercase;
    }

</style>