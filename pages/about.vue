<template>
    <div>
      <Navbar />
      <AboutSection/>
    </div>
  </template>
  
  <script>
  import AboutSection from '~/components/AboutSection.vue';
  import Navbar from '~/components/Navbar.vue';

  export default {
  components: {
    Navbar,
    AboutSection
  },
}
  </script>
  
  <style scoped>
  </style>
  