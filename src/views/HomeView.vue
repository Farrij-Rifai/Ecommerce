<template>
  <div class="home">
    <ComponentsHeader />
    <Com_Carousel />
    <Com_ProdukTerbaru />
    <Com_Galeri />
    <Com_Partner />
    <Com_Footer />
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue';
import ComponentsHeader from "@/components/Com_Header.vue";
import Com_Carousel from "@/components/Com_Carousel.vue";
import Com_ProdukTerbaru from "@/components/Com_ProdukTerbaru.vue";
import Com_Galeri from "@/components/Com_Galeri.vue";
import Com_Partner from "@/components/Com_Partner.vue";
import Com_Footer from "@/components/Com_Footer.vue";

export default {
  name: "HomeView",
  components: {
    ComponentsHeader,
    Com_Carousel,
    Com_ProdukTerbaru,
    Com_Galeri,
    Com_Partner,
    Com_Footer,
  },
};
</script>
