<template>
  <div>
    <h1>List</h1>
    <Card />
  </div>
</template>

<script>
import Card from "./card.vue";

export default {
  name: "HelloWorld",
  components: { Card }
}
</script>

<style scoped>
h1 {
  margin: 10px 2px 0;
}
</style>
