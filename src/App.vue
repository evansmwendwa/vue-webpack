<template>
  <div class="full-width center-content">
    <img src="/static/img/logo.png" alt="" />
    <hello-component name="World" />
  </div>
</template>

<script>
import HelloComponent from './components/HelloComponent.vue'

export default {
  components: {
    HelloComponent
  }
}
</script>
