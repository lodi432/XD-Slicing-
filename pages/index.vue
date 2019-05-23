<template>
  <div>
    <TheHero/>
    <SectionOne/>
    <SectionTwo/>
    <SectionThree/>
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
        title: 'Splicing 🍕',
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
