<template>
  <div class="home">
    <h1>Home</h1>
    <CustomText>Hello World!</CustomText>
    <IconHome width="60" height="60"/>
  </div>
</template>

<script>

import CustomText from '../components/CustomText.vue';
import IconHome from '../icons/home.svg';

export default {
  name: "Home",
  components: {
    CustomText,
    IconHome
  },
};
</script>

<style scoped>
h1 {
  color: red;

  @media (--t) {
    color: blue;
  }
}
</style>