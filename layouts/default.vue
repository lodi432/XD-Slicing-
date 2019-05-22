<template>

  <div class="container">
    <NavbarAlt/>
    <NavbarBottom/>
    <nuxt/>
  </div>
</template>

<script>
  import NavbarAlt from '@/components/NavbarAlt'
  import NavbarBottom from '@/components/NavbarBottom'


  export default {
    components: {
      NavbarAlt, NavbarBottom
    }
  }
</script>

<style>
</style>
