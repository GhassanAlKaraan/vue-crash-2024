<script setup>
import Hero from "@/components/Hero.vue";
import HomeCards from "@/components/HomeCards.vue";
import JobListings from "@/components/JobListings.vue";


</script>

<template>
  <Hero title="Hi bro shou el a5bar" subtitle="Baddak Job?" />
  <HomeCards />
  <JobListings :limit="3" :showButton="true"/>
</template>