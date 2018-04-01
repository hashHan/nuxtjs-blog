<template>
  <div class="container-fluid">
    <TheNavbar/>
    <nuxt/>
  </div>
</template>

<script>
import TheNavbar from '@/components/Navigation/TheNavbar'

export default {
  components: {
    TheNavbar
  },
  data() {
    return {
      //
    }
  }
}
</script>


<style>
html {
  font-family: 'Open Sans', sans-serif;
}

body {
  margin: 0;
}
</style>
