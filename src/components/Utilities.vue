<template>
    <section id="utilities">
        <div class="container h-100">
            <div class="row">
                <div class="special-row col-20">
                    <img class="png-img" src="@/assets/img/buy-comics-digital-comics.png" alt="digital-comics">
                    <p class="u-title">Digital Comics</p>
                </div>

                <div class="special-row col-20">
                    <img class="png-img" src="@/assets/img/buy-comics-merchandise.png" alt="merchandise">
                    <p class="u-title">Dc Merchandise</p>
                </div>

                <div class="special-row col-20">
                    <img class="png-img" src="@/assets/img/buy-comics-subscriptions.png" alt="subscriptions">
                    <p class="u-title">Subscriptions</p>
                </div>

                <div class="special-row col-20">
                    <img class="png-img" src="@/assets/img/buy-comics-shop-locator.png" alt="shop-locator">
                    <p class="u-title">Comic shop locator</p>
                </div>

                <div class="special-row col-20">
                    <img id="power-visa" src="@/assets/img/buy-dc-power-visa.svg" alt="power-visa">
                    <p class="u-title">Dc Power Visa</p>
                </div>
            </div>
        </div>
       


    </section>
  
</template>

<script>
export default {
    name: "Utilities",

}
</script>

<style lang="scss" scoped>
    #utilities {
        background-color: #0282F9;
        padding: 50px 0;
        font-family: sans-serif;
        font-weight: 500;
        text-transform: uppercase;
        color: #fff;
    }

    .special-row {
        display: flex;
        align-items: center;
        justify-content: center;
        cursor: pointer;
    }

    .png-img {
        max-width: 100%;
        height: 60px;
    }

    #power-visa {
        max-width: 100%;
        height: 40px;

    }

    .u-title {
        margin-left: 15px;
        font-size: 0.8em;
    }
</style>