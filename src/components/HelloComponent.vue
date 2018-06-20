<template>
  <h1>Hello {{ name }}!</h1>
</template>

<script>
export default {
  props: {
    name: {
      type: String,
      required: true
    }
  }
}
</script>

<style scoped>
h1 {
  color: #f0f;
  font-weight: 300;
  text-transform: uppercase;
  font-size: 62px;
}
</style>
