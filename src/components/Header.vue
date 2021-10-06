<template>
    <header class="container-fluid" id="bg">
        <!-- logo and icons -->
        <div class="row">
            <div class="col-6 text-center py-4 logo_h">
                <a href="#home"><img src="../assets/img/avadabarbers-logo-x1.png" alt="logo Avada Barbers"></a>
            </div>

            <div class="col-6 d-flex justify-content-center align-items-center py-4">
                <a href="#shopping"><i class="fas fa-shopping-cart"></i></a>
                <a href="#menu"><i class="fas fa-bars"></i></a>
            </div>
        </div>

        <div class="row justify-content-center align-items-center pb-5">
            <div class="col-6">
                <div class="row justify-content-end pb-5">
                    <div class="col-8">
                        <h1>Barber Shop</h1>
                        <div class="br mb-4"></div>
                        <p class="mb-4">The Pinnacle of Male Grooming</p>
                        <button class="btn_header"><a href="#learnMore">LEARN MORE</a></button> 
                    </div>
                </div>                              
            </div>

            <div class="col-6">
                <div class="row justify-content-center pb-5">
                    <div class="col-8 img-h">
                        <img src="../assets/img/avadabarbers_hero_focalmirror-800x1100.png" alt="a barber at work"> 
                    </div>
                    <div class="col-4 d-flex flex-column align-items-end">
                        <div class="m-box text-center py-2 mb-3">
                            <p> {{  }} </p> 
                            <p> Demos </p>
                        </div>

                        <div class="m-box text-center py-2">
                            <p> {{  }} </p>
                            <p> On sale </p>
                        </div>
                    </div>
                </div>     
            </div>
        </div>

    </header>
</template>

<script>
export default {
    name:'Header',
    props: {

  },
}
</script>

<style scoped lang="scss">
@import '../style/general.scss';
@import '../style/variables.scss';

#bg{
    background-image: url(../assets/img/avadabarbers-homepage-hero-bg.jpg);
    background-position: top;
    background-size: cover;
    background-repeat: no-repeat;
    h1{
        color: $bigTitle;
        font-size: 4.5rem;
    }
    p{
        color: $pHeader;
    }
    .fas{
        color: white;
        margin-left: 1.5rem;
        font-size: 0.9rem;
    }
    .fa-bars{
            font-size: 1.5rem;
        }
    .logo_h{
        img{
            height: 3.2rem;
        }
    }
    .m-box{
        background-color: $bigTitle;
        width: 4rem;
        border-radius: 6px;
        p{
            margin: 0;
        }
    }
    .img-h{
        height: 30rem;
        img{
            height: 100%;
        }
    }
    .br{
        width: 50%;
        height: 2px;
        background-color: $refColor;
    }
    .btn_header{
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
}

</style>