<template>
  <div class="page page_theme_light">
    <header>this is header</header>
    <nuxt/>
  </div>
</template>

<style>
.page {
  width: 100%;
  height: 100%;
  border: 1px solid red; /* чтобы видеть границы*/
  border-radius: 8px;
}

.page_theme_light {
  background: #f7f8f9;
  box-shadow: 0px 20px 40px rgba(0, 0, 0, 0.2);
}
</style>

