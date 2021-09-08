<template>
    <section id="jumbotron">
        <div class="container h-100">
            <div class="row"></div>
        </div>
    </section> 
</template>

<script>
export default {
    name: "Hero",

}
</script>

<style lang="scss" scoped>
    #jumbotron {
        background-image: url('../assets/img/jumbotron.jpg');
        height: 400px;
        background-position-x: center;
        background-size: cover;
        background-repeat: no-repeat;
    }
</style>