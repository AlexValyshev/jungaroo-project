<template>
  <div class="cards">
    <Card nameCard="Nulla volutpat aliquam velit"
    textCard="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat ar .."
    profileCard="OZ" dateCard = "05.07.2020" />
    <Card nameCard="Nulla volutpat aliquam velit"
    textCard="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat ar .."
    profileCard="OZ" dateCard = "05.07.2020" />
    <Card nameCard="Nulla volutpat aliquam velit"
    textCard="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat ar .."
    profileCard="OZ" dateCard = "05.07.2020" />
    <Card nameCard="Nulla volutpat aliquam velit"
    textCard="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat ar .."
    profileCard="OZ" dateCard = "05.07.2020" />
    <Card nameCard="Nulla volutpat aliquam velit"
    textCard="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat ar .."
    profileCard="OZ" dateCard = "05.07.2020" />
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
  max-width: 100%;
  max-height: calc(100vh - 173px);
  box-sizing: border-box;
  padding-top: 10px;
  padding-left: 10px;
  overflow-y: auto;
  background: #c4c4c4;
  display: grid;
  grid-template-rows: repeat(auto-fit, minmax(auto, auto));
  grid-row-gap: 20px;

}
</style>
