<script setup>
  import SpellCard from './components/SpellCard.vue'
</script>

<template>
  <img src="./assets/corner-left.webp" alt="" class="corner-ornament" id="top-left">
  <img src="./assets/corner-right.webp" alt="" class="corner-ornament" id="top-right">
  <img src="./assets/corner-bottom-left.webp" alt="" class="corner-ornament" id="bottom-left">
  <img src="./assets/corner-bottom-right.webp" alt="" class="corner-ornament" id="bottom-right">
  <header>
    <h1>Charms</h1>
  </header>
  <spell-card></spell-card>
</template>

<style scoped>
header{
  display: flex;
  align-items: center;
  justify-content: center;
  height: 120px;
  /* background-color: green; */
  color: white;
  font-size: 1.7em;
}

h1 {
  color: white;
  text-shadow: 0px 2px 2px rgb(83, 93, 82);
}
.corner-ornament {
  height: 150px;
  position: absolute;
}

#top-left {
  top: 0;
  left: 0;
}

#top-right{
  top: 0;
  right: 0;
}

#bottom-left {
  bottom: 0;
  left: 0;
}

#bottom-right {
  bottom: 0;
  right: 0;
}
</style>
