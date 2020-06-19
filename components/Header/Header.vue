<template>
<header class="header header_theme_ligth">
  <Logo />
  <Bar />
  <Heading />
  <Button />
</header>

</template>

<script>
import Logo from '~/components/Header/Logo.vue';
import Bar from '~/components/Header/Bar.vue';
import Heading from '~/components/Header/Heading.vue';
import Button from '~/components/Header/Button.vue';

export default {
  components: {
    Logo: Logo,
    Bar: Bar,
    Heading: Heading,
    Button: Button
  }

};


</script>


<style>
.header {
  max-width: 1180px;
  height: 68px;
  margin: 0 auto;
  display: flex;
  flex-direction: row;
  background: #FFFFFF;
  box-shadow: 0px 4px 7px rgba(0, 0, 0, 0.1);
  border-radius: 8px 8px 0px 0px;
}
</style>
