<script>
import AppHeader from './components/AppHeader.vue'
import Content from './components/Content.vue'
import Footer from './components/Footer.vue'
import SignUp from './components/SignUp.vue'



export default {
  components: {
    AppHeader,
    Content,
    Footer,
    SignUp
  }
}
</script>

<template>
  <AppHeader />
  <Content />
  <Footer />
  <SignUp />
</template>

<style lang="scss">
@use './styles/general.scss' as *;
</style>
