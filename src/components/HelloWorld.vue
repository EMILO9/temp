<script>
export default {
  data() {
    return {
      greeting: 'Hello World!'
    }
  }
}
</script>

<template>
  <p class="greeting">{{ greeting }}</p>
</template>

<style lang="scss" scoped>
.greeting {
  color: $base-color;
  font-weight: bold;
}
</style>
