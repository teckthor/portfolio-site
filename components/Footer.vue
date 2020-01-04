<template>
  <div class="container">
      <h1>Desenvolvido por 
        <a href="#" title="Nome do criador do site, Ademar Cardoso">Ademar Cardoso</a>
      </h1>
  </div>  
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css?family=Lexend+Deca&display=swap');
.container {
  font-family: 'Lexend Deca', sans-serif;
  width: 70%;
  height: 5vh;
  display: flex;
  margin: 0 auto;
  text-align: center;
  justify-content: center;
}
.container h1 a {
  font-family: 'Lexend Deca', sans-serif;
  color: black;
  text-decoration-color: black;
}
</style>