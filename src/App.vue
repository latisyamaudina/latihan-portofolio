<template>
  <NavbarComponent style="background-color: antiquewhite;"></NavbarComponent><br><br>
   <HeaderComponent></HeaderComponent><br><br>

  <CardComponent></CardComponent><br><br>
  <ListComponent></ListComponent>
  <FooterComponent style="background-color: antiquewhite;"></FooterComponent>
</template>

<script setup>
import NavbarComponent from './components/NavbarComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import CardComponent from './components/CardComponent.vue';
import ListComponent from './components/ListComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
</script>