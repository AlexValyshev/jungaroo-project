<template>
  <div class="column">
    <TitleColumn class="column__title"></TitleColumn>
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
  max-width: 339px;
}

.column__title {
  margin-bottom: 20px;
}
</style>
