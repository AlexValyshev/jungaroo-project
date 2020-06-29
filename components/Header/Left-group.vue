<template>
<div class="header__left-group">
  <Logo class="header__logo_position" />
  <Bar class="header__bar_position" />
  <Heading class="header__heading_position" />
  <AddButton class="header__add-butoon_position" />
</div>
</template>

<script>
import Logo from '~/components/Header/Logo.vue';
import Bar from '~/components/Header/Bar.vue';
import Heading from '~/components/Header/Heading.vue';
import AddButton from '~/components/Header/Add-button.vue';


export default {
  components: {
    Logo: Logo,
    Bar: Bar,
    Heading: Heading,
    AddButton: AddButton

  }

};
</script>


<style>
.header__left-group {
  display: flex;
  align-items: center;
}

.header__logo_position {
  margin-right: 36px;
}

.header__bar_position {
  margin-right: 15px;
}

.header__heading_position {
  margin: 0 21px 0 0;
}

</style>
