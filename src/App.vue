<template>
  <div>
    <NavbarComponent></NavbarComponent>
   <HeaderComponent></HeaderComponent>
    <ContentComponent></ContentComponent>
    <br>
    <br>
    <ContactComponent></ContactComponent>
    <br>
    <br>
    <FooterComponent></FooterComponent>
  </div>

  </template>

  <script setup>
import HeaderComponent from "../src/components/HeaderComponent.vue"
import NavbarComponent from "../src/components/NavbarComponent.vue"
import ContentComponent from "../src/components/ContentComponent.vue"
import ContactComponent from "../src/components/ContactComponent.vue"
import FooterComponent from "./components/FooterComponent.vue"
</script>