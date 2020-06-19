<template>
  <div class="page page_theme_light">
    <Header />

    <nuxt/>
  </div>
</template>

<script>
import Header from '~/components/Header/Header.vue';
export default {
  components: {
    Header
  }
};
</script>


<style>
.page {
 width: 100%;
  height: 100%;
  border: 1px solid red; /* чтобы видеть границы*/
  border-radius: 8px;
  font-family: 'Open Sans', 'Lato', 'Arial', sans-serif;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

.page_theme_light {
  background: #f7f8f9;
  box-shadow: 0px 20px 40px rgba(0, 0, 0, 0.2);
 }
</style>
