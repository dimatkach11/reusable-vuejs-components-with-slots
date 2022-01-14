<template>
  <AppLayout>
    <template #header>Header</template>
    <AppButton @click="log">
      <AppIcon />
      Press me
    </AppButton>
  </AppLayout>
</template>

<script>
import AppLayout from '@/components/AppLayout.vue'
import AppButton from '@/components/AppButton.vue'
import AppIcon from '@/components/AppIcon'

export default {
  name: 'App',
  components: {
    AppLayout,
    AppButton,
    AppIcon
  },

  methods: {
    log () {
      console.log('clicked')
    }
  }
}
</script>

<style>
*,
*:before,
*:after {
  padding: 0;
  margin: 0;
  border: 0;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

html, body {height: 100%;}

</style>
