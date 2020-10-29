<template>
  <div class="home">
   <HeaderMorayya />
   <HeroSection />
   <ProductMorayya />
   <InstaMorayya />
   <FooterMorayya />

   
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderMorayya from '@/components/HeaderMorayya.vue'
import HeroSection from '@/components/HeroSection.vue'
import ProductMorayya from '@/components/ProductMorayya.vue'
import InstaMorayya from '@/components/InstaMorayya.vue'
import FooterMorayya from '@/components/FooterMorayya.vue'


export default {
  name: 'Home',
  components: {
   HeaderMorayya,
   HeroSection,
   ProductMorayya,
   InstaMorayya,
   FooterMorayya
  }
}
</script>
