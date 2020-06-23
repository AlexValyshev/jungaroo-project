<template>
<header class="header header_theme_ligth">
  <LeftGroup class="header__left-group" />
  <RigthGroup class="header__rigth-group" />
</header>
</template>

<script>
import LeftGroup from '~/components/Header/Left-group.vue';
import RigthGroup from '~/components/Header/Rigth-group.vue';
export default {
  components: {
    LeftGroup: LeftGroup,
    RigthGroup: RigthGroup
  }
};
</script>

<style>
.header {
  max-width: 100%;
  height: 68px;
  margin: 0 auto;
  padding-left: 36px;
  display: flex;
  align-items: center;
  justify-content: space-around;
  border-radius: 8px 8px 0px 0px;
}

.header_theme_ligth {
  background: #FFFFFF;
  box-shadow: 0px 4px 7px rgba(0, 0, 0, 0.1);
}

</style>
