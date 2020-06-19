<template>
    <section  class="columns">
      <Card />
      <Card />
      <Card />
    </section>

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
.columns {
  border: 1px solid red;
}
</style>

