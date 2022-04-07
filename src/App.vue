<template>
  <NavbarView/>
  <ShowCaseView/>
  <NewsletterView/>
  <BoxesView/>
</template>

<script>
import NavbarView from './components/NavbarView.vue'
import ShowCaseView from './components/ShowcaseView.vue'
import NewsletterView from './components/NewsletterView.vue'
import BoxesView from './components/BoxesView.vue'

export default {
  name: 'App',
  components: {
    NavbarView,
    ShowCaseView,
    NewsletterView,
    BoxesView
  }
}
</script>

<style></style>
