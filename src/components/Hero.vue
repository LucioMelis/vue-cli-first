<template>
  <div class="hello">
    <img src="../assets/logotrono.png" alt="logoTrono" />
  </div>
</template>

<script>
export default {
  name: "HeroImg",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
img {
  width: 100px;
}
</style>