<template>
    <section id="footer-links">
        <div class="container h-100">
            <div class="row h-100">

                <div class="col-50">
                    <nav class="special-row-2">
                        <div class="col-25">
                            <ul>DC COMICS
                                <li class="mg-top-10"><a href="#">Characters</a></li>
                                <li><a href="#">Comics</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">TV</a></li>
                                <li><a href="#">Games</a></li>
                                <li><a href="#">Videos</a></li>
                                <li><a href="#">News</a></li>
                            </ul> 

                            <ul class="mg-top-20">SHOP
                                <li class="mg-top-10"><a href="#">Shop Dc</a></li>
                                <li><a href="#">Shop Dc Collectibles</a></li>
                            </ul>
                        </div>
                    

                        <ul class="col-25">DC
                            <li class="mg-top-10"><a href="#">Terms of Use</a></li>
                            <li><a href="#">Privacy policy (New)</a></li>
                            <li><a href="#">Ad Choices</a></li>
                            <li><a href="#">Advertising</a></li>
                            <li><a href="#">Jobs</a></li>
                            <li><a href="#">Subscriptions</a></li>
                            <li><a href="#">Talent Workshops</a></li>
                            <li><a href="#">CPSC Certificates</a></li>
                            <li><a href="#">Ratings</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>

                        <ul class="col-25">SITES
                            <li class="mg-top-10"><a href="#">DC</a></li>
                            <li><a href="#">MAD Magazine</a></li>
                            <li><a href="#">DC Kids</a></li>
                            <li><a href="#">DC Universe</a></li>  
                            <li><a href="#">DC Power Visa</a></li> 
                        </ul>
                    </nav>
                </div>

                <div id="dc-logo-section" class="col-50"></div>

            </div> 
        </div>
    </section>
  
</template>

<script>
export default {
    name: "Footer",

}
</script>

<style lang="scss" scoped>
    #footer-links {
        background-image: url('../assets/img/footer-bg.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        height: 400px;
    }

    #dc-logo-section {
       height: 100%;
       background-image: url('../assets/img/dc-logo-bg.png');
       background-repeat: no-repeat;
       background-size: auto;
       background-position-y: -90px;
    }


    ul {
        margin-right: 20px;
        color: #fff; 
        font-weight: 600; 
        font-size: 1.1em; 

        li a {
            color: #95938f;
            font-family: sans-serif;
            font-weight: 400;
            font-size: 0.7em; 
        }
    }

    
    a:hover {
        color: #0282F9;
    }
</style>