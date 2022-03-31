<template>
<Nav />
<Slide />

</template>

<script>
import Nav from "./components/Nav.vue"
import Slide from "./components/Slide.vue"
export default {
  components : {
    Nav,
    Slide,
  }
}
</script>

<style>
body {
  margin:0px;
  padding: 0px;
  background: rgb(228, 228, 228);
}
</style>