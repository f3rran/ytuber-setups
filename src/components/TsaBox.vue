<template>
  <div id="caja">
      <img :src=miniatura alt="Imagen del producto">
      <h2>{{titulo}}</h2>
      <p>{{info}}</p>
      <a class="enlace" :href="link">Comprar</a>
  </div>
</template>

<script>
export default {
    name: "TsaBox",
    props: {
        miniatura: String,
        titulo: String,
        info: String,
        link: String
    }
}
</script>

<style>
#caja{

    background: white;
    border: black 1px solid;
    margin: 5px;
    padding: 5px;
    border-radius: 5px;
    width: 312px;
    height: auto;

}

img{
    width: 246px;
}

.enlace{
    background: cornflowerblue;
    border: rgb(67, 122, 224) 1px;
    border-radius: 5px;
    text-decoration: none;
    margin: 5px;
    padding: 5px;
    color: white;
}
</style>