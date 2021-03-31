<template>
  <div class="home">
    <CustomText tag="h1">Profile</CustomText>
    <CustomText tag="p">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sint, sit, suscipit! Corporis, cum
      cumque distinctio doloribus eius esse eum fugit ipsum, iusto minus odit provident quam ratione soluta tempore
      voluptates?
    </CustomText>


    <div id="nav">
      <router-link to="/profile/">Post</router-link>
      |
      <router-link to="/profile/igtv">IGTV</router-link>
      |
      <router-link to="/profile/save">Save</router-link>
      |
      <router-link to="/profile/tag">Tag</router-link>
      <router-view/>
    </div>

  </div>
</template>

<script>

import CustomText from '../../components/CustomText.vue'

export default {
  name: "Profile",
  components: {
    CustomText
  },
};
</script>

<style scoped>

</style>