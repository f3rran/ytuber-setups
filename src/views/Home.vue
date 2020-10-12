<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <h1>🔥Productos estrella🔥</h1>
    <div id="container">
      <TsaBox miniatura="https://images-na.ssl-images-amazon.com/images/I/717Di3DGIbL._AC_SL1092_.jpg"
            titulo=" AMD Ryzen 3700X"
            info="Procesador 8 núcleos 16 hilos con arquitectura x86."
            link="https://amzn.to/36WLAuM"  />
    
    <TsaBox miniatura="https://images-na.ssl-images-amazon.com/images/I/51GjnJrTWhL._AC_SL1221_.jpg"
            titulo=" AMD Ryzen 3800X"
            info="Procesador 8 núcleos 16 hilos con arquitectura x86."
            link="https://amzn.to/34UTt1g"  />
    
    <TsaBox miniatura="https://images-na.ssl-images-amazon.com/images/I/71S31CWSs3L._AC_SL1093_.jpg"
            titulo=" AMD Ryzen 3900X"
            info="Procesador 12 núcleos 24 hilos con arquitectura x86."
            link="https://amzn.to/33O5Dta"  />
    </div>
    
  </div>
</template>

<script>
// @ is an alias to /src
import TsaBox from "@/components/TsaBox.vue";

export default {
  name: "Home",
  components: {
    TsaBox
  }
};
</script>

<style scoped>
  #container{
    display: flex;
    justify-content: center;
  }
</style>
