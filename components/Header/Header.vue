<template>
<header class="header header_theme_ligth">
  <LeftGroup class="header__left-group" />
  <RigthGroup class="header__rigth-group" />
  <Logo class="header__logo-position" />
  <Bar class="header__bar-position" />
  <Heading class="header__heading-position" />
  <AddButton class="header__addbutoon-position" />
  <SearchButton class="header__searchbutton-position" />
  <SearchInput class="header__searchinput-position" />
  <Bell class="header__bell-position" />
  <Bar class="header__bartwo-position" />
  <Avatar class="header__avatar-position" />
  <AvatarName class="header__avatarname-position" />
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

.header__logo-position {
  margin-right:  36px;
}

.header__bar-position {
  margin-right:  15px;
}

.header__heading-position {
  margin-right: 10px;
}

.header__addbutoon-position {
  margin-right: 346px;
}

.header__searchbutton-position {
  margin-right: 16px;
}

.header__searchinput-position {
  margin-right: 150px;

}

.header__bell-position {
  margin-right: 28px;
}

.header__bartwo-position {
  margin-right: 28px;
}

.header__avatar-position {
  margin-right: 16px;
}

.header__avatarname-position {
  margin-right: 32px;
}
</style>
