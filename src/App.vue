<script>
import AppHeader from './components/AppHeader.vue'
import Content from './components/Content.vue'
import Footer from './components/Footer.vue'



export default {
  components: {
    AppHeader,
    Content,
    Footer
  }
}
</script>

<template>
  <AppHeader />
  <Content />

  <Footer />
</template>

<style lang="scss">
@use './styles/general.scss' as *;
</style>
