<template>
    <section>
      <app-header></app-header>
      <app-whylogo></app-whylogo>
      <app-calculator></app-calculator>
      <app-bonus></app-bonus>
      <app-footer></app-footer>
    </section>
</template>


<script>
import appHeader from '../../components/logo/AppHeader.vue'
import AppWhylogo from "../../components/logo/AppWhylogo.vue"
import AppCalculator from "../../components/logo/AppCalculator.vue"
import AppBonus from "../../components/logo/AppBonus.vue"
import AppFooter from "../../components/logo/AppFooter.vue"
export default {
  components: {
    appHeader,
    AppWhylogo,
    AppCalculator,
    AppBonus,
    AppFooter
  },
}
</script>

<style scoped lang='sass'>
  
</style>