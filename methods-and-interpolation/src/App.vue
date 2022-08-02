<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Home from './components/views/Home.vue';
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />
    <div class="wrapper">
      <Home/>
      <HelloWorld msg="You did it!!!" />
    </div>
  </header>

  <main>

  </main>
</template>

<style scoped>
header {
  text-align: center;
}

</style>
