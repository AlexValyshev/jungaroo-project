<template>
<button type="button" class="header__search-button header__search-button_theme_ligth">
  <img class="button__image butoon__image_theme_ligth" src="~/assets/images/search.svg" alt="Search">
</button>
</template>

<style>
.header__search-button {
  width: 20px;
  height: 20px;
  border: none;
  padding: 0 0;
  transition: .3s;
  cursor: pointer;
}

.header__search-button:active {
  outline: none;
}

.header__search-button:focus {
  outline: none;
}

.header__search-button_theme_ligth {
  background-color: rgba(0, 50, 50, 0);
}

.button__image {
  width: 20px;
  height: 20px;
}
</style>
