<template>
  <main class="container-fluid">
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
    <section class="row" id="services">
      
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
</style>
