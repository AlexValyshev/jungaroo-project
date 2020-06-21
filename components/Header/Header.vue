<template>
<header class="header header_theme_ligth">
  <Logo class="header__logo_position" />
  <Bar class="header__bar_position" />
  <Heading class="header__heading_position" />
  <AddButton class="header__add-butoon_position" />
  <SearchButton class="header__search-button_position" />
  <SearchInput class="header__search-input_position" />
  <Bell class="header__bell_position" />
  <Bar class="header__bar-two_position" />
  <Avatar class="header__avatar_position" />
  <AvatarName class="header__avatar-name_position" />

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
  display: flex;
  align-items: center;
  border-radius: 8px 8px 0px 0px;
}

.header_theme_ligth {
  background: #FFFFFF;
  box-shadow: 0px 4px 7px rgba(0, 0, 0, 0.1);
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

.header__add-butoon_position {
  margin: auto 346px auto 0;
}

.header__search-button_position {
  margin: auto 16px auto 0;
}

.header__search-input_position {
  margin: auto 150px auto 0;

}

.header__bell_position {
  margin: auto 28px auto 0;
}

.header__bar-two_position {
  margin: auto 28px auto 0;
}
.header__avatar_position {
  margin: auto 16px auto 0;
}

.header__avatar-name_position {
  margin: auto 32px auto 0;
}
</style>
