<template>
  <div id="app">
    <Header />
    <Main :products="products" />
    <Footer :socials="socials" />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer,
  },
  data(){
    return{
      products:[
        {
          name: 'Brush',
          price: 15,
          img:require(`./assets/img/brush_dark-800x800.png`),
          alt:'image brush',
        },
        {
          name: 'Scissors',
          price: 85,
          img:require(`./assets/img/scissors-800x800.png`),
          alt:'image Scissors',
        },
        {
          name: 'Hot Oil',
          price: 15,
          img:require(`./assets/img/hot_oil_dark-800x800.png`),
          alt:'image Hot Oil',
        },
        {
          name: 'Straight Razor',
          price: 30,
          img:require(`./assets/img/straight_razor_dark-800x800.png`),
          alt:'image Straight Razor',
        },
      ],
      socials:[
        {
          nome:'facebook',
          url:'#facebook',
          class:'fab fa- fa-facebook',
        },
        {
          nome:'twitter',
          url:'#twitter',
          class:'fab fa- fa-twitter',
        },
        {
          nome:'youtube',
          url:'#youtube',
          class:'fab fa- fa-youtube',
        },
        {
          nome:'instagram',
          url:'#instagram',
          class:'fab fa- fa-instagram',
        }
      ]
    }
  },
  
}
</script>

<style lang="scss">
@import './style/general.scss';

#app {
  font-family: Arial, Helvetica, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
