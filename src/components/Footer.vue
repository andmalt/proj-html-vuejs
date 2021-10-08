<template>
  <footer class="container-fluid text-center py-2" id="footer">
    <!-- main section -->
    <section class="row justify-content-center py-5" id="f-m">

      <div class="col-3 f-img pb-2">
        <img src="../assets/img/avadabarbers_footer_shop_image-700x546.png" alt="image products Avada Barbers">
        <a href="#">SHOP OUR RANGE NOW</a>
      </div>

      <div class="col-3 f-img pb-2">
        <div>

        </div>

        <div>

        </div>

        <div>

        </div>
      </div>

      <div class="col-3 f-img pb-2">
        <img src="../assets/img/avadabarbers_footer_appointment_image-800x624.png" alt="image Barber at work">
        <a href="#">BOOK YOUR APPOINTMENT</a>
      </div>

    </section>

    <!-- footer of the footer -->
    <section id="f-f">

    </section>
  </footer>
</template>

<script>
export default {
    name:'Footer',
    props: {

  },
}
</script>

<style scoped lang="scss">
@import '../style/variables.scss';

#footer{
  background-color: $bg;
  .f-img{
    img{
      height: 15rem;
      padding-bottom: 1.5rem;
    }
    a{
      padding: 0.7rem 1.5rem;
      border:2px solid $refColor;
      color: $refColor;
      text-decoration: none;
    }
  }
}

</style>