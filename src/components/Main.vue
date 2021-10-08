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

      <div class="col-12 text-center mb-5">
        <button class="btn_main"><a href="#readAboutourServices">READ ABOUT OUR SERVICES</a></button>
      </div>
      <!-- black triangle -->
      <div class="col-12">
        <div class="triangle">
          <!-- svg -->
        </div>
      </div>

    </section>

    <!-- section products -->
    <section class="row pb-5" id="products-m">
      <!-- title -->
      <div class="col-12 text-center py-3 mb-5">
        <h6>WE HAVE YOU CONCERED</h6>
        <h2>Avada Groming Products</h2>
      </div>

      <!-- products -->
      <Box :product="element" v-for="(element , index ) in products" :key="index" />

      <!-- button -->
      <div class="col-12 text-center mb-5">
        <button class="btn_main"><a href="#shopOurProductRange">SHOP OUR PRODUCT RANGE</a></button>
      </div>
    </section>

    <!-- product advertisement -->
    <div class="row justify-content-center mb-5 pb-5">
      <div class="col-8" id="advertisement">
        <div class="row">
          <div class="col-5 bg_p text-center">
            <img src="../assets/img/shaving_butter-800x800.png" alt="image shaving butter">
          </div>

          <div class="col-7 bg-o">
            <div class="p-5 ">
              <h6>THIS MONTHS FEATURED PRODUCT</h6>
              <h2>Shaving Butter</h2>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum illum natus rerum exercitationem obcaecati beatae deserunt maxime neque asperiores!</p>
              <button class="btn_main"><a href="#buyNow">BUY NOW</a></button>
            </div>
          </div>
        </div>
      </div>
    </div>
    
    <!-- section reviews -->
    <section class="row justify-content-center pb-5" id="reviews">
      <div class="col-12 text-center py-3 mb-5">
        <h6>WHAT PEOPLE SAY</h6>
        <h2>Reviews</h2>
      </div>

      <div class="col-3 text-center">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatum dolore similique veniam repellat nostrum explicabo molestias temporibus expedita, ipsum, veritatis laboriosam aliquid amet vel illo itaque at modi voluptate eos!</p>
        <img src="../assets/img/avadabarbers-trimcut-gallery6.jpg" alt="photo John Doe">
        <p><em>John Doe</em></p>
      </div>

      <div class="col-3 text-center">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatum dolore similique veniam repellat nostrum explicabo molestias temporibus expedita, ipsum, veritatis laboriosam aliquid amet vel illo itaque at modi voluptate eos!</p>
        <img src="../assets/img/avadabarbers-trimcut-gallery7.jpg" alt="photo Pete Jones">
        <p><em>Pete Jones</em></p>
      </div>

      <div class="col-3 text-center">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatum dolore similique veniam repellat nostrum explicabo molestias temporibus expedita, ipsum, veritatis laboriosam aliquid amet vel illo itaque at modi voluptate eos!</p>
        <img src="../assets/img/avadabarbers-trimcut-gallery3.jpg" alt="photo Mark Wilkson">
        <p><em>Mark Wilkson</em></p>
      </div>

    </section>

    <!-- section blog post -->
    <section class="row justify-content-center" id="blog-post">
      <div class="col-12 mb-5">
        <div class="triangle">
          <!-- svg -->
        </div>
      </div>

      <!-- title -->
      <div class="col-12 text-center py-3 mb-5">
        <h6>TALES FROM THE BARBER SHOP</h6>
        <h2>Recent Blog Posts</h2>
      </div>

      <!-- columns -->
      <div class="col-3 text-center">
        <img src="../assets/img/avadabarbers-second-blog-700x441.jpg" alt="image avada barbers">
        <h4>Avada Barbers Now Open</h4>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati blanditiis sapiente animi quis id reiciendis eaque quod tenetur pariatur quos hic illo aut alias optio sunt voluptatem quam, nobis recusandae.</p>
      </div>

      <div class="col-3 text-center">
        <img src="../assets/img/avadabarbers-choosing-blog-700x441.jpg" alt="image local Avada Barbers">
        <h4>Choosing The Right Barber</h4>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati blanditiis sapiente animi quis id reiciendis eaque quod tenetur pariatur quos hic illo aut alias optio sunt voluptatem quam, nobis recusandae.</p>
      </div>

      <div class="col-3 text-center">
        <img src="../assets/img/avadabarbers-ourservice-blog-700x441.jpg" alt="image barber at work">
        <h4>Quick Service Guide</h4>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati blanditiis sapiente animi quis id reiciendis eaque quod tenetur pariatur quos hic illo aut alias optio sunt voluptatem quam, nobis recusandae.</p>
      </div>

      <!-- button -->
      <div class="col-12 text-center my-5">
        <button class="btn_main"><a href="#readAboutourServices">READ MORE FROM OUR BLOG</a></button>
      </div>

    </section>
  </main>
</template>

<script>
import Box from './Box.vue'

export default {
  name: 'Main',
  props: {
    products:Array,
  },
  components:{
    Box,
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../style/variables.scss';

h6{
color: $refColor;
font-weight: 600;
}
h4{
  color: $refColor;    
}
h2{
  color: $titles;
  font-size: 3.5rem;
  font-weight: 600;
}
p{
  color: $pHeader;
}
.btn_main{
  background-color: rgba( 0, 0, 0, 0);
  padding: 0.7rem 1.5rem;
  border-color: $refColor;
  color: $refColor;
  &:hover{
    border-color: $hoverRef;
    color: $hoverRef;
  }
  a{
    color: $refColor;
    text-decoration: none;
    font-size: 0.9rem; 
    &:hover{
      color: $hoverRef;
    } 
  }
}

#after-h{
  background-image: url(../assets/img/avadabarbers-about-introbackground.jpg); 
  background-position: top;
  background-size: cover;

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
  .box-s{
    margin-bottom: 3.5rem;

    img{
      height: 5rem;
      margin-bottom: 2rem;
    }
    h4{
      margin-bottom: 2rem;
    }

  }
  .triangle{
    height: 5rem;
    background-image: url(../assets/triangle.svg);
    background-position: top;
    background-repeat: no-repeat;
    background-size: contain;
    transform: scaleX(20);
    filter: brightness(0) saturate(100%) invert(4%) sepia(2%) saturate(5488%) hue-rotate(211deg) brightness(84%) contrast(91%);
  }
}
#products-m{
  background-image: url(../assets/img/avadabarbers-reviewsbackground.jpg); 
  background-position: top;
  background-size: cover;
}
#advertisement{
  border-top: 4px solid $refColor;
  position: relative;
  z-index: 2;
  right: 40px;
  bottom: 40px;

  .bg_p{
    background-image: url(../assets/img/avadabarbers-cta-background.jpg);
    background-position: center;
    background-size: cover;
    img{
      height: 20rem;
    }
  }
  .bg-o{
    background-color: $bg;
    
  }
}
#reviews{
  em{
    color: $refColor;
    font-weight: 600;
  }
  img{
    height: 6rem;
    border-radius: 50%;
    margin-bottom: 1rem;
  }
}
#blog-post{
  background-color: $bigTitle;

  img{
    height: 12rem;
    margin-bottom: 1.2rem;
  }
  .triangle{
    height: 5rem;
    background-image: url(../assets/triangle.svg);
    background-position: top;
    background-repeat: no-repeat;
    background-size: contain;
    transform: scaleX(20) rotate(0.5turn);
  }
  h4{
    font-weight: 600;    
  }
}
</style>
