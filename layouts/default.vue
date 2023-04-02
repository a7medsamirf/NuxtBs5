<template>
  <div class="layout">
    <the-header />
    <Nuxt  />

    <the-footer />
  </div>
</template>

<script>
import TheFooter from '~/components/Footer/TheFooter.vue'
import TheHeader from '~/components/Header/TheHeader.vue'
export default {
  components: { TheHeader, TheFooter },

}
</script>

<style>

</style>