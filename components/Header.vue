<template>

  <div class="container-component">
    <img class="background" src="../static/asset-background.png" alt="Imagem de fundo do header do site">

      <!-- Este componente de Header terá a nossa foto, links 
      das nossas redes sociais. -->
  <figure class="image">
    <img class="image-perfil" src="../static/asset-perfil-image.jpeg" alt="Imagem de perfil do Ademar Cardoso, desenvolvedor deste site.">
  </figure>

  <p class="name-perfil">
    Ademar Cardoso
  </p>

  <div class="links-bio">
    <a href="https://github.com/teckthor" title="Link para a conta do github"><i class="fab fa-github"></i></a>
    <a href="http://#" title="Link para a conta do medium"><i class="fab fa-medium"></i></a>
    <a href="http://#" title="Link para a conta do instagram"><i class="fab fa-instagram"></i></a>
    <a href="http://#" title="Link para a conta do linkedin"><i class="fab fa-linkedin"></i></a>
  </div>

  </div>  
</template>

<script>
export default {
  name: "Header"
}
</script>

<style>
.container-component {
  max-width: 100% !important;
}
figure { padding-top: 45px; }
figure .image-perfil {
  display: flex;
  margin: 0px auto;
  width: 20%;
  position: relative;
  border-radius: 20px;
}
.links-bio {
  text-align: center;
}
a i {
  margin-top: 15px;
  margin-left: 20px;
  font-size: 2em;
  transition: all .3s;
}
a i:hover{
  -moz-transform: scale(1.2);
	-webkit-transform: scale(1.2);
  transform: scale(1.2);
}
.name-perfil {
  font-size: 1.8em;
  text-align: center;
}
.name-perfil::after {
  content: "_";
  animation: blink 0.8s ease-in-out infinite;
}

@keyframes blink {
  0%, 100% { opacity: 0; }
  50% { opacity: 1; }
}

.background {
  margin: 0 auto;
  display: block;
  width: 100% !important;
  position: absolute;
  height: 350px;
  filter: brightness(50%);
}

</style>