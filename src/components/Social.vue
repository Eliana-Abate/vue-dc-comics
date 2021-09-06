<template>
    <section id="social">
        <div class="container h-100">
            <div class="row h-100">

                <div class="col-50">
                    <div id="sign-up-box">
                        <h4>SIGN-UP NOW!</h4>
                    </div> 
                </div>

                <div class="col-50">
                    <div class="special-row-3">
                        <h3>FOLLOW US</h3>
                        <ul class="special-row-3">
                            <li class="clickable"><img src="@/assets/img/footer-facebook.png" alt="facebook"></li>
                            <li class="clickable"><img src="@/assets/img/footer-twitter.png" alt="twitter"></li>
                            <li class="clickable"><img src="@/assets/img/footer-youtube.png" alt="youtube"></li>
                            <li class="clickable"><img src="@/assets/img/footer-pinterest.png" alt="pinterest"></li>
                            <li class="clickable"><img src="@/assets/img/footer-periscope.png" alt="periscope"></li>
                        </ul>
                    </div>
                    
                        
                    
                </div>
            </div> 
        </div>
    </section>
</template>

<script>
export default {
    name: "Social",

}
</script>

<style scoped>
    #social {
        background-color: #303030;
        padding: 20px 0;
    }

    #sign-up-box {
        padding: 10px 15px;
        width: 100px;
        color: #fff;
        border: 2px solid #0282F9;
        text-align: center;
    }

    #sign-up-box:hover {
        background-color: #0282F9;
    }

    #sign-up-box h4 {
        margin: 0;
        padding: 0;
    }

    .special-row-3 {
        display: flex;
        align-items: center;
        justify-content: flex-end;
    }

    .special-row-3 h3 {
        color: #0282F9;
    }
    
    ul {
        list-style-type: none;   
    }

    ul li {
        margin: 0 10px;
    }

    li:hover img {
        opacity: 0.8;
    }

</style>