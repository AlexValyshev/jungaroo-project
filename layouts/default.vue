<template>
  <div class="page">
    <header>this is header</header>
    <nuxt/>
  </div>
</template>

<style>
body {
  width: 100%;
  margin: 0;
  background: #f2f2f2;
  padding: 126px 0;
  font-family: 'Open Sans', 'Lato', 'Arial', sans-serif;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

.page {
  max-width: 1180px;
  height: 771px;  /* потом нужно убрать, сформируется по высоте контента*/
  border: 1px solid red; /* чтобы видеть границы*/
  margin: 0 auto;
  background: #f7f8f9;
  border-radius: 8px;
  box-shadow: 0px 20px 40px rgba(0, 0, 0, 0.2);
}

</style>

