<script setup>
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <link href="/src/style.css" rel="stylesheet" />

  <div class="bg-linear-180 from-blue-400 via-purple-400 to-rose-400">
    <h1 class="text-orange-300 text-5xl ml-5">Color Collection</h1>

    <h3 class="ml-5 text-3xl">
      An assortment of color palettes which can be used for any project
    </h3>

    <br />

    <button class="bg-ffbf00 p-3 ml-5 border-4">#FFBF00</button>
    <button class="bg-00ff40 p-3 ml-5 border-4">#00FF40</button>
    <button class="bg-0040ff p-3 ml-5 border-4">#0040FF</button>
    <button class="bg-ff00c0 p-3 ml-5 border-4">#FF00C0</button>

    <br /><br />

    <hr class="solid" />
  </div>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Italianno&display=swap");

div {
  font-family: Italianno;
}
</style>
