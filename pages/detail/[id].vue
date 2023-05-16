<template>
  <h2>{{ route.params.id }}</h2>
</template>
<script lang="ts" setup>
  const route = useRoute()
</script>
<style scoped lang="scss">
h2 {
  color: $linkColor
}
</style>