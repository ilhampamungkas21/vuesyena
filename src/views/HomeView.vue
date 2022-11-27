<template>
  <div class="home">

    <HeaderSyena/>
    <HeroSyena/>
    <WomenSyena/>
    <InstaSyena/>
    <PartnerSyena/>
    <FooterSyena/>



  </div>
</template>

<script>
// @ is an alias to /src
import HeaderSyena from '@/components/HeaderSyena.vue'
import HeroSyena from '@/components/HeroSyena.vue'
import WomenSyena from '@/components/WomenSyena.vue'
import InstaSyena from '@/components/InstaSyena.vue'
import PartnerSyena from '@/components/PartnerSyena.vue'
import FooterSyena from '@/components/FooterSyena.vue'


export default {
  name: 'HomeView',
  components: {
    HeaderSyena,
    HeroSyena,
    WomenSyena,
    InstaSyena,
    PartnerSyena,
    FooterSyena,
  
  }
}
</script>
