<template>
  <div id="app">
    <header>
       <NavBar />
    </header>
    <main>
      <router-view header="Game Play"></router-view>
    </main>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
  export default {
    name: 'App',
    components: {
      NavBar
    }
  }
</script>
