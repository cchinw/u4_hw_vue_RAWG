<template>
  <div class="card game-card">
    <div class="image-wrapper">
      <img :src="image" />
    </div>
    <div class="info-wrapper flex-col">
      <h3>{{name}}</h3>
    </div>
    <div>{{rating}}</div>
  </div>
</template>

<script>
  export default {
    name: 'GameCard',
    props: ['name', 'image', 'rating']
  }
</script>
