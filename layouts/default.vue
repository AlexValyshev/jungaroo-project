<template>
  <div class="page page_theme_light">
    <Header class="header"/>
    <SideBar class="sidebar"/>
    <nuxt/>
  </div>
</template>

<script>
import Header from "~/components/Header/Header.vue"
import SideBar from "~/components/SideBar.vue";
export default {
  components: {
    SideBar,
    Header
  }
};

</script>

<style>
.page {
  display: grid;
  width: 100%;
  height: 100%;
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

.header {
  position: relative;
  z-index: 1;
}
.sidebar {
  position: absolute;
  top: 0;
  left: 0;
}
</style>
