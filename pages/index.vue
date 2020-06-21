<template>
    <section  class="columns">
      <Card />
      <Card />
      <Card />
    </section>

</template>

<script>
import Header from '~/components/Header/Header.vue'
import Card from "~/components/Card.vue";
export default {
  components: {
    Header,
    Card
  }
};
</script>

<style>
.columns {
  padding-left: 72px;
  border: 1px solid red;
}
</style>
