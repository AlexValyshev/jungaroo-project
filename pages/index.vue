<template>
  <Columns></Columns>
</template>

<script>
import Columns from "~/components/Columns.vue";
export default {
  components: {
    Columns
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
