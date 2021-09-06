<template>
    <section id="footer-links">
        <div class="container h-100">
            <div class="row h-100">

                <div class="col-50">
                    <nav>
                        <ul class="row">
                            <li v-for = "(link, index) in links" :key="index"><a :href="link.url">{{link.text}}</a></li>
                        </ul>
                    </nav>
                </div>

                <div id="dc-logo-section" class="col-50">
                    <div id="dc-logo-bg">
                        <img src="@/assets/img/dc-logo-bg.png" alt="">
                    </div>
                </div>
            </div> 
        </div>
    </section>
  
</template>

<script>
export default {
    name: "Footer",

}
</script>

<style scoped>
    #footer-links {
        background-image: url('../assets/img/footer-bg.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        height: 400px;
    }

    #dc-logo-section {
       padding-top: 50px;
    }



</style>