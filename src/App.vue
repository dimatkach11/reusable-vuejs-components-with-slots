<template>
  <div id="app">
    <AppButton @click="log">
      <AppIcon />
      Press me
    </AppButton>
  </div>
</template>

<script>
import AppButton from './components/AppButton.vue'
import AppIcon from '@/components/AppIcon'

export default {
  name: 'App',
  components: {
    AppButton,
    AppIcon
  },

  methods: {
    log () {
      console.log('ciao')
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
