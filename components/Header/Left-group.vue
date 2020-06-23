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
  width: 50%;
  display: flex;
  align-items: center;
  justify-content: flex-start;

}

.header__logo_position {
  margin: auto 36px;
}

.header__bar_position {
  margin: auto 15px auto 0;
}

.header__heading_position {
  margin: auto 10px auto 0;
}

</style>
