<template>
  <main class="container-fluid">
    <!-- section after header -->
    <section class="row" id="after-h">
      <div class="col-12 d-flex justify-content-center">
        <div class="p-5 text-center ">
          <h6>AWARD WINNING</h6>
          <h2>Pro Barbers</h2>
          <button class="btn_main"><a href="#meetYourNewBarber">MEET YOUR NEW BARBER</a></button>
        </div>
      </div>
      <div class="col-12">
        <div class="triangle">
          <!-- svg -->
        </div>
      </div>
    </section>
    <!-- section services -->
    <section class="row justify-content-center px-5" id="services">
      <!-- title -->
      <div class="col-12 text-center py-1 mb-5">
        <h6>MENS GROOMING</h6>
        <h2>Services</h2>
      </div>
      <!-- services  -->
      <div class="col-3">
        <div class="box-s text-center">
          <img src="../assets/img/avadabarbers-trimcut-icon-before.png" alt="trimcut icon">
          <h4>Trim &amp; Cut</h4>
          <p>Avada Barbers are experts in the lickety split trim and hair cut. Quick but careful and ridiculously good looking.</p>
        </div>
      </div>

      <div class="col-3">
        <div class="box-s text-center">
          <img src="../assets/img/avadabarbers-washndry-icon.png" alt="washndry icon">
          <h4>Wash &amp; Dry</h4>
          <p>Take a seat in our fine leather chairs, lean back and let us  lather you a fresh head in a luxurious fashion.</p>
        </div>
      </div>

      <div class="col-3">
        <div class="box-s text-center">
          <img src="../assets/img/avadabarbers-beardtrim-icon.png" alt="beardtrim icon">
          <h4>Beard Tidy</h4>
          <p>Tame the tangles and untidy facial hairs like a gentlemen with our Beard Tidy services from Avada Barbers.</p>
        </div>
      </div>

      <div class="col-12 text-center">
        <button class="btn_main"><a href="#readAboutourServices">READ ABOUT OUR SERVICES</a></button>
      </div>

    </section>
    
  </main>
</template>

<script>
export default {
  name: 'Main',
  props: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../style/general.scss';
@import '../style/variables.scss';

#after-h{
  background-image: url(../assets/img/avadabarbers-about-introbackground.jpg); 
  background-position: top;
  background-size: cover;
  h6{
    color: $refColor;
  }
  h2{
    color: $titles;
    font-size: 3.5rem;
  }
  .btn_main{
    background-color: rgba( 0, 0, 0, 0);
    padding: 0.7rem 1.5rem;
    border-color: $refColor;
    color: $refColor;
    a{
      color: $refColor;
      text-decoration: none;
      font-size: 0.9rem;  
    }
  }
  .triangle{
    height: 5rem;
    background-image: url(../assets/triangle.svg);
    background-position: top;
    background-repeat: no-repeat;
    background-size: contain;
    transform: scaleX(20);
  }

}
#services{
  h6{
    color: $refColor;
  }
  h2{
    color: $titles;
    font-size: 3.5rem;
  }
  .btn_main{
    background-color: rgba( 0, 0, 0, 0);
    padding: 0.7rem 1.5rem;
    border-color: $refColor;
    color: $refColor;
    a{
      color: $refColor;
      text-decoration: none;
      font-size: 0.9rem;  
    }
  }
  .box-s{
    margin-bottom: 3rem;

    img{
      height: 5rem;
      margin-bottom: 2rem;
    }
    h4{
      color: $refColor;
      margin-bottom: 2rem;
    }
    p{
      color: $pHeader;
    }
  }
}
</style>
