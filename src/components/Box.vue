<template>
  <div class="col-3 box-product text-center">
      <img :src="product.img" :alt=" product.alt ">
      <h4> {{ product.name }} </h4>
      <p> &dollar; {{ product.price }}.00 </p>
  </div>
</template>

<script>

export default {
    name: 'Box',
    props: {
        product:Object,
  }
}
</script>

<style scoped lang="scss">
@import '../style/variables.scss';

.box-product{
    margin-bottom: 3.5rem;

    img{
      height: 15rem;
      margin-bottom: 2rem;
    }
    h4{
      color: $refColor;
      margin-bottom: 2rem;
      font-weight: 600;
    }
    p{
      color: $refColor;
    }
}
</style>