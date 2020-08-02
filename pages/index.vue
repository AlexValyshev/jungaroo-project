<template>
<page class="page page_theme_light">
  <Columns></Columns>
</page>
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
.page {
  display: grid;
  grid-template-areas:
    "header header"
    "sidebar columns";
  width: 100%;
  height: 100%;
  border-radius: 8px;
  font-family: 'Open Sans', 'Lato', 'Arial', sans-serif;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
</style>
