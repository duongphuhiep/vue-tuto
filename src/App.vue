<template>
  <div id="app">
    <Hero />
  </div>
</template>

<script>
import Hero from './home/Hero.vue';
export default {
  name: 'app',
  components: {Hero},
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
