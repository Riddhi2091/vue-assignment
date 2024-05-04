<script setup>
import NavbarComponent from "@/components/NavbarComponent.vue"
import HeroComponent from '@/components/HeroComponwnt.vue'
import LifeCycle from '@/components/LifeCycle.vue'
import AboutComponent from '@/components/AboutComponent.vue'
import FooterComponent from '@/components/FooterComponent.vue'
import AOS from "aos";
import "aos/dist/aos.css";

AOS.init({
  duration: 1000,
  easing: 'ease-in-sine',
});

</script>

<template>
  <main>
    <NavbarComponent />
    <HeroComponent />
    <LifeCycle />
    <AboutComponent />
    <FooterComponent />
  </main>
</template>

<style scoped></style>
