<template>
  <div class="cards">
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
  height: calc(100vh - 173px);
  box-sizing: border-box;
  padding-top: 10px;
  padding-left: 10px;
  padding-bottom: 30px;
  overflow-y: scroll;
  background: #c4c4c4;
  display: grid;
  grid-template-rows: repeat(auto-fit, minmax(158px, 1fr));
  grid-row-gap: 20px;

}
</style>
