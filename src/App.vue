<template>
  <div class="app">
    <MasterHeader/>
    <main class="main">
      <Container>
        <router-view/>
      </Container>
    </main>
  </div>
</template>


<script>

import MasterHeader from './components/Header.vue'
import Container from './components/Container.vue'

export default {
  name: "App",
  components: {
    MasterHeader,
    Container
  }
}

</script>

<style scoped>
.main {
  padding-top: 40px;
}
</style>