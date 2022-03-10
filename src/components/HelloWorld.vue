<template>
  <div>
    <div v-for="item in 6" :key="item">
      <div class="tile" v-for="item in 5" :key="item"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.tile {
  border: 1px solid grey;
  width: 3.5rem;
  height: 3.5rem;
  display: inline-block;
  margin:0.1rem
}
</style>
