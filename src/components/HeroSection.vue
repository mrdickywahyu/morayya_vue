<template>
     <!-- Hero Section Begin -->
    <section class="hero-section">
        <carousel class="hero-items" :items="1" :nav="false">
            <div class="single-hero-items set-bg" style="background-image: url('/img/hero-1.jpg')">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <img src="img/logo_website_morayya1.png" alt="" />
                           
                            <p>
                                Moms And Baby Wear
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </div>
            
        </carousel>
    </section>
    <!-- Hero Section End -->
</template>



<script>


import carousel from 'vue-owl-carousel'

export default {
    name: 'HeroSection',
    components : {
        carousel
    }
}
</script>