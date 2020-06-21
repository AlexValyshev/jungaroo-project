<template>
<header class="header header_theme_ligth">
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
import Logo from '~/components/Header/Logo.vue';
import Bar from '~/components/Header/Bar.vue';
import Heading from '~/components/Header/Heading.vue';
import AddButton from '~/components/Header/Add-button.vue';
import SearchButton from '~/components/Header/Search-button.vue';
import SearchInput from '~/components/Header/Search-input.vue';
import Bell from '~/components/Header/Bell.vue';
import Avatar from '~/components/Header/Avatar.vue';
import AvatarName from '~/components/Header/Avatar-name.vue';


export default {
  components: {
    Logo: Logo,
    Bar: Bar,
    Heading: Heading,
    AddButton: AddButton,
    SearchButton: SearchButton,
    SearchInput: SearchInput,
    Bell: Bell,
    Avatar: Avatar,
    AvatarName: AvatarName
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
