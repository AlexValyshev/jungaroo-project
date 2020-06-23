<template>
  <div class="column">
    <TitleColumn></TitleColumn>
    <Cards></Cards>
  </div>
</template>

<script>
import TitleColumn from "~/components/TitleColumn.vue";
import Cards from "~/components/Cards.vue";
export default {
  components: {
    TitleColumn,
    Cards
  }
};
</script>

<style>
.column {
  max-width: 336px;
}
</style>