<template>
  <div id="app">
     <h1>Hello App!</h1>
        <p>
            <router-link to="/foo">Go to Foo</router-link>
            <router-link to="/bar">Go to Bar</router-link>
        </p>
        <router-view></router-view>
  </div>
</template>

<script>
	
import Hero from './home/Hero.vue';
import Vue from 'vue';

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
