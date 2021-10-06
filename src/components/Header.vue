<template>
    <header class="container-fluid" id="bg">
        <!-- logo and icons -->
        <div class="row">
            <div class="col-6 text-center py-4 logo_h">
                <img src="../assets/img/avadabarbers-logo-x1.png" alt="logo Avada Barbers">
            </div>

            <div class="col-6 d-flex justify-content-center align-items-center py-4">
                <a href="#shopping"><i class="fas fa-shopping-cart"></i></a>
                <a href="#menu"><i class="fas fa-bars"></i></a>
            </div>
        </div>

        <div>

        </div>

        <div>

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
    height: 600px;
    .fas{
        color: white;
        margin-left: 1.2rem;
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
}

</style>