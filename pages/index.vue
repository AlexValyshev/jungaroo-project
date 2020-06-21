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
  border: 1px solid blue;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-column-gap: 12px;
  max-width: 1076px;
  margin: auto;
  padding-left: 72px;
}
</style>
