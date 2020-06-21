<template>
<a class="header__bell-container" href='/'>
  <img class="header__bell header__bell_theme_ligth" src="~/assets/images/bell.svg" alt="Оповещение">
  <div class="header__bell-ring header__bell-ring_theme_ligth"></div>
</a>
</template>

<style>
.header__bell-container {
  max-width: 21px;
  max-height: 20px;
  border: none;
  position: relative;
  transition: .3s;
  cursor: pointer;
}

.header__bell-container:hover {
  opacity: .6;
}

.header__bell-ring {
  width: 8px;
  height: 8px;
  border-radius: 50%;
  position: absolute;
  top: 0;
  right: 0;
}

.header__bell-ring_theme_ligth {
  background: #3591FB;
}


.header__bell {
  width: 21px;
  height: 20px;
}
</style>
