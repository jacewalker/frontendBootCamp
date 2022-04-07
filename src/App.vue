<template>
  <NavbarView/>
  <ShowCaseView/>
  <NewsletterView/>
  <BoxesView/>
  <LearnView/>
  <FAQView/>
  <InstructorsView/>
</template>

<script>
import NavbarView from './components/NavbarView.vue'
import ShowCaseView from './components/ShowcaseView.vue'
import NewsletterView from './components/NewsletterView.vue'
import BoxesView from './components/BoxesView.vue'
import LearnView from './components/LearnView.vue'
import FAQView from './components/FAQView.vue'
import InstructorsView from './components/InstructorsView.vue'

export default {
  name: 'App',
  components: {
    NavbarView,
    ShowCaseView,
    NewsletterView,
    BoxesView,
    LearnView,
    FAQView,
    InstructorsView
  }
}
</script>

<style></style>
