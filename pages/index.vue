<template>
  <div class="Main">
   <p>Main Page</p>
  </div>
</template>

<script lang="ts" setup>
const { $sayHello } = useNuxtApp()
$sayHello("Felipe")
</script>

<style scoped>

</style>