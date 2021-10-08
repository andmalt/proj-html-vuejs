<template>
  <footer class="container-fluid text-center py-1" id="footer">
    <!-- main section -->
    <section class="row justify-content-center pt-3 pb-5" id="f-m">

      <div class="col-3 f-img pb-2">
        <img src="../assets/img/avadabarbers_footer_shop_image-700x546.png" alt="image products Avada Barbers">
        <a href="#">SHOP OUR RANGE NOW</a>
      </div>

      <div class="col-3 p-2">
        
        <div class="f-img-l mb-5">
          <!-- logo -->
          <img src="../assets/img/avadabarbers-logo-x1.png" alt="logo Avada Barbers">

          <p>Avada Barbers 123 <br> New York Street <br> New York City <br> info@yourwebsite.com <br> +1(555)555-1212</p>
        </div>

        <div id="socials">
          <h6>FOLLOW US</h6>
          <ul class="d-flex justify-content-center">
            <li><a href="#facebook" class="fab fa- fa-facebook"></a></li>
            <li><a href="#twitter" class="fab fa- fa-twitter"></a></li>
            <li><a href="#youtube" class="fab fa- fa-youtube"></a></li>
            <li><a href="#instagram" class="fab fa- fa-instagram"></a></li>
          </ul>
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
  .f-img-l{
    padding: 0 4rem;
    img{
      height: 3rem;
      margin-bottom: 1.5rem;
    }
    p{
      color: $titles;
    }
  }
}
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