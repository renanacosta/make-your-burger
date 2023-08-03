<template>
  <div id="main-banner">
    <h1>Make Your Burger</h1>
  </div>
</template>

<script>
export default {
  name: "Banner",
};
</script>

<style scoped>
#main-banner {
  background-image: url('/public/img/burger.jpg');
  background-position: 0; /* Ajuste a posição da imagem conforme necessário */
  background-size: cover;
  height: 40rem; /* Altura responsiva em relação à fonte do elemento raiz */
  display: flex;
  align-items: center;
  justify-content: flex-start;
}

#main-banner h1 {
  color: #fff;
  text-align: center;
  font-size: 4rem; /* Tamanho da fonte responsiva em relação à fonte do elemento raiz */
  background-color: #222;
  padding: 2rem 4rem; /* Preenchimento responsivo em relação à fonte do elemento raiz */
}
</style>
