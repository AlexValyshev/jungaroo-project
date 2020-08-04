<template>
  <h2 class="title title_theme_light">{{name}}</h2>
</template>

<script>
export default {
  props: {
    name: {
      type: String
    },
  },
};
</script>

<style>
@font-face {
  font-family: 'Open Sans';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url('~assets/fonts/OpenSans-Regular.ttf') format('ttf');
}
@font-face {
  font-family: 'Lato';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url('~assets/fonts/Lato-Black.ttf') format('ttf');
}

.title {
  font-family: 'Open Sans', 'Lato', 'Arial', sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 33px;
  margin: 0;
  margin-bottom: 20px;
}

.title_theme_light {
  color: #272a43;
}
</style>
