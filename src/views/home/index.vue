<template>
  <div class="home">
    
    <div class="timeline">
      <h1>Home</h1>
      <CustomText>Hello World!</CustomText>
      <IconHome width="60" height="60"/>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A, commodi corporis dolor ducimus esse itaque maxime nam neque quasi qui repellendus rerum sapiente tempore tenetur, ullam? Eius reiciendis repellendus voluptates?</p>
    </div>
    <div class="sidebar">
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ab aspernatur, at debitis deserunt dicta dignissimos expedita illum pariatur quibusdam quidem sit totam? Eius mollitia odio officia quae quos soluta voluptatum.</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium consequatur et eveniet ex facere facilis impedit incidunt laborum, maiores mollitia nisi porro praesentium quaerat quibusdam, repellat sit suscipit, totam ullam.</p>
    </div> 
  </div>
</template>

<script>

import CustomText from '../../components/CustomText.vue';
import IconHome from '../../icons/home.svg';

export default {
  name: "Home",
  components: {
    CustomText,
    IconHome
  },
};
</script>

<style scoped>
.home {
  max-width: 605px;
  margin-left:auto;
  margin-right: auto;
  
  @media (--t) {
    max-width: none;
    display: grid;
    grid-template-columns: 1fr 295px;
    grid-gap: 30px;
  }
}
.sidebar {
  display: none;
  
  @media (--t) {
    display: block;
  }
}
</style>