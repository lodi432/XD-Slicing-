
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
  import TheHero from '@/components/Hero/TheHero'
  import SectionOne from '@/components/Sections/SectionOne'
  import SectionTwo from '@/components/Sections/SectionTwo'
  import SectionThree from '@/components/Sections/SectionThree'
  import Carousel from '@/components/Corusel/Carousel'
  import MobileStrategy from '@/components/Sections/MobileStrategy'
  import Featured from '@/components/Sections/Featured'
  import Footer from '@/components/Footer/Footer'
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
