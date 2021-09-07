<template>
    <section id="main-header">
        <div class="container h-100">
            <div class="row h-100">

                <div id="header-logo" class="col-40 row">
                    <img src="@/assets/img/dc-logo.png" alt="dc-logo">
                </div>

                <div class="col-60">
                    <nav>
                        <ul class="row">
                            <li v-for = "(link, index) in links" :key="index" v-on:click = "selectedLink(index)">
                                <a :href="link.url" :class="{active: link.current}">{{link.text}}</a>
                                <div :class="{notch: link.current}"></div>
                            </li>
                        </ul>
                    </nav>
                </div>
            </div> 
        </div>
    </section>
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

    methods: {
        selectedLink: function(index) {

            this.links.forEach((item, i) => {
            
             item.current = (i == index);
               /*if (i == index) {
                   item.current = true;
               } else {
                   item.current = false;
               }*/
            });
        },
    },

}
</script>

<style lang="scss" scoped>
    #main-header {
        background-color: #fff;
        height: 120px;

        #header-logo {
            img {
                width: 80px;
            }  
        }
    }

    ul {
        li {
        height: 120px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        position: relative;
        
            a {
            color:  #464646;
            padding: 15px;
            text-transform: uppercase;
            text-align: center;
            &.active {
                 color: #0282F9;
                }
            }
        }
    }
    
   

    .notch {
        width: 40px;
        height: 4px;
        background-color: #0282F9;  
        position: absolute;
        bottom: 0;
        left: 50%;
        transform: translateX(-50%);
    }
</style>