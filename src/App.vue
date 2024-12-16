<script setup>
import Navbar from './components/Navbar.vue';
import { RouterView } from 'vue-router';

import Hero from './components/Hero.vue';
import HomeCards from './components/HomeCards.vue';
import JobListings from './components/JobListings.vue';


 


</script>
<template>
     <Navbar />
     <RouterView />
     <!--<Hero  />-->
     <!--<Hero title="Test Title" subTitle="Test SubTitle" />-->
     <!--<HomeCards />-->
     <!--<JobListings :limit="3" :show-button="true" />-->
</template>