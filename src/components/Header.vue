<template>
  <header class="row">
      <div id="header-logo">
          <img src="@/assets/img/dc-logo.png" alt="dc-logo">
      </div>

      <div>
          <nav>
              <ul>
                  <li v-for = "(link, index) in links" :key="index"><a :href="link.url">{{link.text}}</a></li>
              </ul>
          </nav>
      </div>

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

<style>
    header {
        background-color: #fff;
        height: 120px;
    }

</style>