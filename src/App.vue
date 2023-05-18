<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  components: { AppHeader, AppFooter, AppMain },

}
</script>

<template>
  <header>
    <app-header />
  </header>
  <main>
    <app-main />
  </main>
  <footer>
    <app-footer />
  </footer>
</template>

<style lang="scss">
 @use './assets/styles/general.scss';

</style>

