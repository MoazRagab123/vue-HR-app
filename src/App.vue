<script setup>
import NavBar  from './components/NavBar.vue';
import Hero from './components/Hero.vue'
import HomeCards from './components/HomeCards.vue';
import JobListings from './components/JobListings.vue';
</script>

<template>
    <NavBar/>
    <Hero />
    <HomeCards/>
    <JobListings :showButton="true" :limit="3"/>
</template>

<style>
</style>