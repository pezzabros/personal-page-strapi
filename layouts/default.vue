<template>  
  <div>
    <Header />
    <div class="uk-section uk-section-default">
      <div class="uk-container uk-container-large">
        <nuxt />
      </div>
    </div>

  </div>
</template>

<script>
// Import your new Header component
import Header from '~/components/Header.vue'
export default {
  components: {
    Header
  }
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
}
</style>
