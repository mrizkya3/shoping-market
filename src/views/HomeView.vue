<template>
  <div class="home">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
     
    <HeaderView/>
    <HeroShop/>
    <WomanShop/>
    <InstagramShop/>
    <PartnerShop/>
    <FooterShop/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderView from '@/components/HeaderView.vue'
import HeroShop from '@/components/HeroShop.vue'
import WomanShop from '@/components/WomanShop.vue'
import InstagramShop from '@/components/InstagramShop.vue'
import PartnerShop from '@/components/PartnerShop.vue'
import FooterShop from '@/components/FooterShop.vue'





export default {
  name: 'HomeView',
  components: {
    HeaderView,HeroShop,WomanShop,InstagramShop,PartnerShop,FooterShop
  }
}
</script>
