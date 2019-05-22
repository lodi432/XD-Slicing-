
<template>
  <div>
    <TheHero/>
    <SectionOne/>
    <SectionTwo/>
    <<SectionThree/>
    <Carousel/>
    <MobileStrategy/>
    <Featured/>
    <Footer/>
  </div>
</template>

<script>
  import TheHero from '@/components/TheHero'
  import SectionOne from '@/components/SectionOne'
  import SectionTwo from '@/components/SectionTwo'
  import SectionThree from '@/components/SectionThree'
  import Carousel from '@/components/Carousel'
  import MobileStrategy from '@/components/MobileStrategy'
  import Featured from '@/components/Featured'
  import Footer from '@/components/Footer'
  export default {
    components: {
      TheHero, SectionTwo, SectionThree, Carousel, MobileStrategy, Featured , SectionOne, Footer
    },
    head () {
      return {
        title: 'Home Page 🍕',
        meta: [
          { name: 'twitter:title', content: 'Nuxt Fundamentals by Vue School'},
          { name: 'twitter:description', content: 'Nuxt + Vue School = 🍕'},
          { name: 'twitter:image', content: 'https://i.imgur.com/UYP2umJ.png'},
          { name: 'twitter:card', content: 'summary_large_image'}
        ]
      }
    },
    computed: {
    }
  }
</script>

<style scoped>
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }
  .title {
    font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
    display: block;
    font-weight: 300;
    font-size: 100px;
    letter-spacing: 1px;
  }
  .subtitle {
    font-weight: 300;
    font-size: 42px;
    color: #526488;
    word-spacing: 5px;
  }
  .links {
    padding-top: 15px;
  }
</style>
