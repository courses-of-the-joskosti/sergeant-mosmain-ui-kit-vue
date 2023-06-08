<script lang="ts">
export default {
  data() {
    return {}
  }
}
</script>

<template>
  <div>
    <RouterLink to="/">Home</RouterLink> | 
    <RouterLink to="/notHome">Not Home</RouterLink>
  </div>
  <RouterView />
</template>

<style scoped>
</style>
