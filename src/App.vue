<template>
  <NavbarView/>
  <ShowCaseView/>
  <NewsletterView/>
</template>

<script>
import NavbarView from './components/NavbarView.vue'
import ShowCaseView from './components/ShowcaseView.vue'
import NewsletterView from './components/NewsletterView.vue'

export default {
  name: 'App',
  components: {
    NavbarView,
    ShowCaseView,
    NewsletterView
  }
}
</script>

<style></style>
