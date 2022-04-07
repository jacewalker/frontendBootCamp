<template>
  <NavbarView/>
  <ShowCaseView/>
  <NewsletterView/>
  <BoxesView/>
  <LearnView/>
  <FAQView/>
</template>

<script>
import NavbarView from './components/NavbarView.vue'
import ShowCaseView from './components/ShowcaseView.vue'
import NewsletterView from './components/NewsletterView.vue'
import BoxesView from './components/BoxesView.vue'
import LearnView from './components/LearnView.vue'
import FAQView from './components/FAQView.vue'

export default {
  name: 'App',
  components: {
    NavbarView,
    ShowCaseView,
    NewsletterView,
    BoxesView,
    LearnView,
    FAQView,
  }
}
</script>

<style></style>
