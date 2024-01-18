<script setup>
import {  RouterView } from 'vue-router'
import MainHeader from './components/header/MainHeader.vue';
import MainFooter from './components/footer/MainFooter.vue';
</script>

<template>
  <MainHeader/>
  <RouterView />
  <MainFooter/>
</template>
