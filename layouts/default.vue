<template>
  <div>
    <Nuxt class="main" />
    <Footer />
  </div>
</template>

<script>
import Footer from '../components/Footer'

export default {
  components: {
    Footer,
  },
}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background-color: #f4e9e2;
}

.main {
  padding-bottom: 100px;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}
</style>
