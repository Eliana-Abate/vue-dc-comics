<template>
    <header>
        <section class="container h-100">
            <div class="row h-100">

                <div id="header-logo" class="col-40 row">
                    <img src="@/assets/img/dc-logo.png" alt="dc-logo">
                </div>

                <div class="col-60">
                    <nav>
                        <ul class="row">
                            <li v-for = "(link, index) in links" :key="index"><a :href="link.url">{{link.text}}</a></li>
                        </ul>
                    </nav>
                </div>
            </div> 
        </section>
    </header>
</template>

<script>
export default {
    name: "Header",
    data() {
        return {
            links: [
                {
                    text: 'Characters',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Comics',
                    url: '#',
                    current: true,
                },
                {
                    text: 'Movies',
                    url: '#',
                    current: false,
                },
                {
                    text: 'TV',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Games',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Collectibles',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Videos',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Fans',
                    url: '#',
                    current: false,
                },
                {
                    text: 'News',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Shop',
                    url: '#',
                    current: false,
                },
            ],

        };
    },

}
</script>

<style scoped>
    header {
        background-color: #fff;
        height: 120px;
    }

    img {
        width: 80px;
       
    }

    ul {
        list-style-type: none;   
    }

    ul li a {
        text-decoration: none;
        color:  #464646;
        padding: 15px;
        text-transform: uppercase;
    }
</style>