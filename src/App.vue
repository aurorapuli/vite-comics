<script>
import AppHeader from './components/AppHeader.vue'
import Content from './components/Content.vue'
import AppFooter from './components/AppFooter.vue'
import SignUp from './components/SignUp.vue'



export default {
  components: {
    AppHeader,
    Content,
    AppFooter,
    SignUp
  }
}
</script>

<template>
  <AppHeader />
  <Content />
  <AppFooter />
  <SignUp />
</template>

<style lang="scss">
@use './styles/general.scss' as *;
</style>
