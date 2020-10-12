<template>
  <div id="main">
      <h1>Vegetta 777</h1>
      <div id="card">
          <img src="https://esports.as.com/2020/01/07/Vegetta.png?hash=619afe072e4d1934a50f2e7fd1c0911b51a74e2c" alt="">
          <p>Vegetta777 tiene el título de ser el segundo youtuber español con más suscriptores del mundo: más de 28 millones en 2020. De hecho, es el creador de contenido de Minecraft más grande de España gracias al éxito de sus episodios de 'Planeta Vegetta'.</p>
      </div>
      <div id="container">
          <TsaBox miniatura="https://images-na.ssl-images-amazon.com/images/I/71sfWTrYfwL._AC_SL1500_.jpg"
            titulo="AMD Ryzen Threadripper 3960x"
            info="Procesador 24 núcleos 48 hilos con arquitectura x86."
            link="https://amzn.to/34NitHv"  />

            <TsaBox miniatura="https://images-na.ssl-images-amazon.com/images/I/81wTPPCp--L._AC_SL1500_.jpg"
            titulo="ASUS ROG Strix TRX40-E Gaming"
            info="Placa Base Gaming sTRX4 para 3a Generación AMD Ryzen Threadripper con 16 etapas de Potencia, Wi-Fi 6, 2.5 Gbps LAN, USB 3.2 Gen 2, SATA, Tres M.2, OLED y Aura Sync RGB"
            link="https://amzn.to/3nHkfT9"  />

            <TsaBox miniatura="https://images-na.ssl-images-amazon.com/images/I/91Qg5K-cmfL._AC_SL1500_.jpg"
            titulo="ASUS ROG Strix GeForce RTX 2080 Ti OC Edition"
            info="Tarjeta gráfica (11 GB, GDDR6, 352 bits, 7680 x 4320 Pixeles, PCI Express 3.0)"
            link="https://amzn.to/36W0gu1"  />

            <TsaBox miniatura="https://images-na.ssl-images-amazon.com/images/I/61ViJczDahL._AC_SL1000_.jpg"
            titulo="Lian Li pc-o11wgx"
            info="Premium PC Case"
            link="https://amzn.to/3nB6PrM"  />
      </div> 
  </div>
</template>

<script>
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
  #card{
      margin: 0px  auto;
      display:flex;
      width:820px;
  }
  p{
      text-align: justify;
      margin: 25px;
  }
</style>