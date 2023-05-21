<template>
  <div>
    <!-- <app-header></app-header> -->
    <!-- <hello-world></hello-world> -->
    <HelloWorld msg="Welcome to Your Vue.js"></HelloWorld>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import AppHeaderVue from './components/AppHeader.vue'

export default {
  data: function() {
    return {
      str: 'hi'
    }
  },
  components: {
    // 'app-header' : AppHeaderVue
    HelloWorld,
    'hello-world' : HelloWorld,
  }
}
</script>

<style>

</style>