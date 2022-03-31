<template>
  <div>
    <img src="../assets/imagenes/ofertas.gif" alt="slide" />
    <img class="astronaut1" src="../assets/imagenes/500_92.png" alt="" />
  </div>
</template>

<script>
export default {};
</script>

<style>
img {
  z-index: -1;
  margin-top: 10px;
  object-fit: cover;
  width: 100%;
  height: 300px;
}

.astronaut1 {
  position: absolute;
  z-index: 1;
  width: 400px;
  height: 400px;
  top: 20%;
  left: 60%;
}

@media screen and (max-width: 900px) {
  .astronaut1 {
    position: absolute;
    z-index: 1;
    width: 150px;
    height: 150px;
    top: 30%;
    left: 60%;
  }
}
</style>