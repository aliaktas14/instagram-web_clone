<template>
  <header class="container">
    <slot/>
  </header>
</template>

<script>

export default {
  name: "Container",
}
</script>

<style scoped>

.container {
  max-width: 940px;
  margin-left: auto;
  margin-right: auto;
}

</style>