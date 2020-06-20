<template>
  <section class="columns">
    <TitleColumn />
    <Card />
    <Card />
    <Card />
  </section>
</template>

<script>
import Card from "~/components/Card.vue";
import TitleColumn from "~/components/TitleColumn.vue";

export default {
  components: {
    Card,
    TitleColumn
  }
};
</script>

<style>
.columns {
  border: 1px solid red;
}
</style>

