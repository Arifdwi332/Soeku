<template>
  <div class="home">
    <HeaderSoeku />
    <HeroSoeku />
    <ProductSoeku />
    <InstaSoeku />
    <PartnerSoeku />
    <FooterSoeku />
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import HeaderSoeku from '@/components/HeaderSoeku.vue' 
import HeroSoeku from '@/components/HeroSoeku.vue' 
import ProductSoeku from '@/components/ProductSoeku.vue' 
import InstaSoeku from '@/components/InstaSoeku.vue' 
import PartnerSoeku from '@/components/PartnerSoeku.vue' 
import FooterSoeku from '@/components/FooterSoeku.vue' 

export default {
  name: 'Home',
  components: {
    //HelloWorld
    HeaderSoeku,
    HeroSoeku,
    ProductSoeku,
    InstaSoeku,
    PartnerSoeku,
    FooterSoeku
  }
}
</script>
