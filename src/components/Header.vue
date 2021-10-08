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
                    <div class="col-8 h-h">
                        <h1>Barber Shop</h1>
                        <div class="br mb-4"></div>
                        <p class="mb-4">The Pinnacle of Male Grooming</p>
                        <a href="#learnMore">LEARN MORE</a>
                    </div>
                </div>                              
            </div>

            <div class="col-6">
                <div class="row justify-content-center pb-5">
                    <div class="col-8 img-h">
                        <img src="../assets/img/avadabarbers_hero_focalmirror-800x1100.png" alt="a barber at work"> 
                    </div>
                    <div class="col-4 d-flex flex-column align-items-end" id="h-box"> 
                        <div class="m-box">
                            <div id="box1">
                                <p><a href="#shop"><i class="fas fa-cart-arrow-down"></i></a> </p> 
                                <p> Demos </p>
                            </div>

                            <div id="box2">
                                <p> &dollar; 39.00 </p>
                                <p> On sale </p>
                            </div>
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
@import '../style/variables.scss';

#bg{
    background-image: url(../assets/img/avadabarbers-homepage-hero-bg.jpg);
    background-position: top;
    background-size: cover;
    background-repeat: no-repeat;
    h1{
        color: $bigTitle;
        font-family: $fontTitle;
        font-size: 4.3rem;
        font-weight: 600;
    }
    p{
        color: $pHeader;
        font-size: 1.2rem;
        font-family: $fontParag;
    }
    .h-h{
        a{
            color: $refColor;
            text-decoration: none;
            padding: 0.7rem 1.5rem;
            border:2px solid $refColor;
            font-size: 0.9rem; 
            font-family: $fontParag;
            &:hover{
                color: $hoverRef;
                border-color: $hoverRef;
            } 
        }
    }
    
    .fas{
        color: white;
        margin-left: 1.5rem;
        font-size: 0.9rem;
        &:hover{
                color: $hoverRef;
            } 
    }
    .fa-bars{
            font-size: 1.5rem;
            &:hover{
                color: $hoverRef;
            } 
        }
    .logo_h{
        img{
            height: 3.2rem;
        }
    }
    #h-box{

        .m-box{   
            position: fixed;         
            width: 4rem;
            z-index: 5;
            height: 12rem;
            
            #box1,
            #box2{
                width: 100%;
                height: 4rem;
                margin-bottom: 1rem;
                background-color: $titles;
                border-radius: 6px;
                display: flex;
                flex-direction: column;
                justify-content: center;
                align-items: center;

                .fas{
                    color: $pHeader;
                    margin: 0;
                }
                p{
                    margin: 0;
                    font-size: 1rem;
                    text-align: center;
                }
            }
            
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
}

</style>