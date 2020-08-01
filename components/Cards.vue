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
  max-height: calc(100vh - 173px);
  box-sizing: border-box;
  padding-top: 10px;
  padding-left: 10px;
  overflow-y: auto;
  background: #c4c4c4;
  display: grid;
  grid-template-rows: repeat(auto-fit, minmax(158px, auto));
  grid-row-gap: 20px;

}
</style>
