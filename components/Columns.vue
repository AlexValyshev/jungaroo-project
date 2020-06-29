<template>
  <section class="columns">
    <Column></Column>
    <Column></Column>
    <Column></Column>
  </section>
</template>

<script>
import Column from "~/components/Column.vue";
export default {
  components: {
    Column
  }
};
</script>

<style>
.columns {
  height: calc(100vh - 86px);
  padding-left: 106px;
  padding-top: 34px;
  box-sizing: border-box;
  display: grid;
  /* grid-template-columns: repeat(auto-fit, fit-content(339px)); */
  grid-auto-flow: column;
  grid-auto-columns: 339px;
  grid-column-gap: 12px;
  /* overflow-x: scroll; */
}
</style>
