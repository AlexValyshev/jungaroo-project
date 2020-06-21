<template>
  <div class="cards cards__background">
    <Card></Card>
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
import Cards__background from "~/components/Cards__background.vue";
export default {
  components: {
    Card,
    Cards__background
  }
};
</script>

<style>
.cards {
  width: 100%;
  height: 536px;
  overflow-y: auto;
  display: grid;
  grid-template-rows: repeat(3, 1fr);
  grid-row-gap: 20px;
  padding-left: 10px;
  padding-top: 10px;
}
</style>