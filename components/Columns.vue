<template>
<section class="columns">
  <Column></Column>
  <Column></Column>
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
  max-width: 100%;
  height: calc(100vh - 68px);
  padding-left: 34px;
  margin-right: 34px;
  padding-top: 34px;
  box-sizing: border-box;
  display: grid;
  grid-template-columns: repeat(auto-fit, fit-content(339px));
  grid-auto-flow: column;
  grid-auto-columns: 339px;
  column-gap: 12px;
  overflow-x: auto;
  grid-area: columns;
}
</style>
