<template>
  <div class="home">
    <HeaderNava />
    <HeroNava />
    <BannerNava />
    <InstaNava />
    <PartnerNava />
    <FooterNava />
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import HeaderNava from "@/components/HeaderNava.vue";
import HeroNava from "@/components/HeroNava.vue";
import BannerNava from "@/components/BannerNava.vue";
import InstaNava from "@/components/InstaNava.vue";
import PartnerNava from "@/components/PartnerNava.vue";
import FooterNava from "@/components/FooterNava.vue";

export default {
  name: "HomeView",
  components: {
    HeaderNava,
    HeroNava,
    BannerNava,
    InstaNava,
    PartnerNava,
    FooterNava,
  },
};
</script>
