<template>
    <div id="socials">
        <h6>FOLLOW US</h6>
        <ul class="d-flex justify-content-center">
        <li v-for="(element, index) in socials" :key="index"><a :href="element.url" :class="element.class"></a></li>
        </ul>
    </div>
</template>

<script>
export default {
    name:'Socials',
    props:{
        socials:Array,
    }
}
</script>

<style lang="scss">
@import '../style/variables.scss';

#socials{
  h6{
    color: $refColor;
    font-weight: 600;
  }
  ul{
    padding: 0;

    li{
      margin: 0.5rem;
      list-style: none;
      a{
        color: $titles;
        text-decoration: none;
      }
    }
  }
}
</style>