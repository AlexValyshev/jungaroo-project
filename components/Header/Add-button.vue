<template>
<button type="button" class="header__add-button header__add-button_theme_ligth ">Add new</button>
</template>

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
.header__add-button {
  width: 77px;
  height: 27px;
  border-radius: 5px;
  font-family: 'Open Sans', 'Lato', 'Arial', sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 13px;
  line-height: 18px;
  border: none;
  transition: .3s;
  cursor: pointer;
}

.header__add-button_theme_ligth {
  color: white;
  background: #856FF5;

}

.header__add-button:active {
  outline: none;
}

.header__add-button:focus {
  outline: none;
}

.header__add-button:hover {
  opacity: .6;
}
</style>
