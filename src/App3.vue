<template>
  <div class="full-width center-content">
    <hello-component name="World1"/>
    <hello-component name="World2"/>
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
