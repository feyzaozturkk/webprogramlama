<template>
  <v-app>
    
    <v-main>
      <UyeGiris />
      <Uyelik/>
       <Kategoriler/>
        <Secenekler/>
        <Ayakkabiturleri/>
         <Foto/>
         <Ayakkabilar/>
         <Arama/>
         <Sepet/>
         <Siparis/>
        
    </v-main>
  </v-app>
</template>

<script>
import UyeGiris from "./components/UyeGiris";
import Uyelik from "./components/Uyelik";
import Kategoriler from "./components/Kategoriler";
import Secenekler from "./components/Secenekler";
import Ayakkabiturleri from "./components/Ayakkabiturleri";
import Foto from "./components/Foto";
import Ayakkabilar from "./components/Ayakkabilar";
import Arama from "./components/Arama";
import Sepet from "./components/Sepet";
import Siparis from "./components/Siparis";
export default {
  name: "App",

  components: {
    UyeGiris,
    Uyelik,
    Kategoriler,
    Secenekler,
    Ayakkabiturleri,
    Foto,
    Ayakkabilar,
    Arama,
    Sepet,
    Siparis,
  },

  data: () => ({
    //
  })
};
</script>
