<template>
<!-- Este componente terá os cards com informçoes de projetos 
Realizados por mim.   -->
<div class="card">
  <div class="card-image">
    <figure class="image is-1by1">
      <img src="" alt="Placeholder image">
    </figure>
  </div>
  <div class="card-content" v-for="item in items" :key="item.id">
    <div class="media">
      <div class="media-content" 
         >

        <p class="title is-4">{{ item.title }}</p>

      </div>
    </div>

    <div class="content">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit.
      Phasellus nec iaculis mauris. <a>@bulmaio</a>.
      <br>
    </div>
  </div>
</div>

</template>

<script>
export default {
  name: "Cards",
  data() {
    return {
      items: [{
        title: 'Ersi',
        description: 'Um site com as informações do evento ERSI, que acontecerá na Unigranrio',
        url: 'http://#',
        image: ''
      }
      ]
    }
  }

}
</script>

<style>
.card {
  width: 70%;
  margin: 20px auto;
  width: 20%;
  transition: all .3s ease-in-out;
  border-radius: 10px; 
  padding: 10px;
}
.card:hover{
  cursor: pointer;
  transform: scale(1.01);
  box-shadow: .5em 0 .5em rgb(119, 117, 117);
}

</style>