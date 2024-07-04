<template>
  <div>
    <Navbar />
    <HeroSection />
  </div>
</template>

<script>
import HeroSection from '~/components/HeroSection.vue';
import about from '~/pages/about.vue';
import ProjectsSection from '~/components/ProjectsSection.vue';
import contact from '~/pages/contact.vue';
import Navbar from '~/components/Navbar.vue';
import project from './project.vue';

export default {
  components: {
    HeroSection, contact, about, project
  }
}
</script>./Index.vue
