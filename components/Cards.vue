<template>
  <div class="cards">
    <Card></Card>
    <Card></Card>
    <Card></Card>
    <Card></Card>
    <Card></Card>
    <Card></Card>
  </div>
</template>

<script>
import Card from "~/components/Card.vue";
export default {
  components: {
    Card
  }
};
</script>

<style>
.cards {
  width: 100%;
  height: 536px;
  overflow-y: auto;
  background: #c4c4c4;
  display: grid;
  grid-template-rows: repeat(3, 1fr);
  grid-row-gap: 20px;
  padding: 10px 0 12px 10px;
}
</style>