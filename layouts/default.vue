<template>

  <div class="container">
    <NavbarAlt/>
    <NavbarBottom/>
    <nuxt/>
  </div>
</template>

<script>
  import NavbarAlt from '@/components/Navbar/NavbarAlt'
  import NavbarBottom from '@/components/Navbar/NavbarBottom'


  export default {
    components: {
      NavbarAlt, NavbarBottom
    }
  }
</script>

<style>
</style>
