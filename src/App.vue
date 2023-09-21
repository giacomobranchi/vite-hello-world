<script>
import appTitle from './components/AppTitle.vue'
export default {

  data() {
    return {
      hello: 'Hello Vite!'

    }
  },
  components: {
    appTitle
  }
}
</script>

<template>
  <appTitle></appTitle>
  <h1>{{ hello }}</h1>
</template>

<style></style>
