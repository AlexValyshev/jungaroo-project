<template>
  <div class="column">
    <TitleColumn name="name Column" />
    <Cards />
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
  width: 100%;
}

</style>
