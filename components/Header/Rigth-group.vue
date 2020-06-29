<template>
<div class="header__rigth-group">
  <SearchButton class="header__search-button_position" />
  <SearchInput class="header__search-input_position" />
  <Bell class="header__bell_position" />
  <Bar class="header__bar-two_position" />
  <Avatar class="header__avatar_position" />
  <AvatarName class="header__avatar-name_position" />
</div>
</template>

<script>
import SearchButton from '~/components/Header/Search-button.vue';
import SearchInput from '~/components/Header/Search-input.vue';
import Bell from '~/components/Header/Bell.vue';
import Bar from '~/components/Header/Bar.vue';
import Avatar from '~/components/Header/Avatar.vue';
import AvatarName from '~/components/Header/Avatar-name.vue';


export default {
  components: {
    SearchButton: SearchButton,
    SearchInput: SearchInput,
    Bell: Bell,
    Bar: Bar,
    Avatar: Avatar,
    AvatarName: AvatarName
  }

};
</script>


<style>
.header__rigth-group {
  display: flex;
  align-items: center;
}

.header__search-button_position {
  margin-right: 16px;
}

.header__search-input_position {
  margin-right: 150px;

}

.header__bell_position {
  margin-right: 28px;
}

.header__bar-two_position {
  margin-right: 28px;
}

.header__avatar_position {
  margin-right: 16px;
}

.header__avatar-name_position {
  margin-right: 32px;
}
</style>
