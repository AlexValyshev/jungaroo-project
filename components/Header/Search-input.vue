<template>
<form class="header__search-form" name="search-form">
  <input type="text" placeholder="Search for .." name="search-inpute" class="header__search-input header__search-input_theme_ligth ">
</form>
</template>

<style>
.header__search-form {
  width: 84px;
  height: 20px;

}

.header__search-input {
  width: 100%;
  height: 100%;
  border: none;
  font-family: 'Open Sans', 'Arial', sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 20px;
  text-overflow: ellipsis;
  white-space: nowrap;
  overflow: hidden;
}

.header__search-form_theme_ligth {
  color: #C5CACD;
}
</style>
