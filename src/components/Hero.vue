<template>
  <div class="hello">
    <img src="../assets/casate.png" alt="trono" />
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
  width: 250px;
}
</style>