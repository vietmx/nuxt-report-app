<template>
  <section class="home">
    <h1 class="home__heading">Welcome to your Report App!</h1>
    <incident-card :incidents="incidents"></incident-card>
  </section>
</template>

<script>
import incidentCard from "@/components/incidentCard.vue";
export default {
  name: "landing-page",
  data() {
    return {
      incidents: []
    };
  },
  components: {
    incidentCard
  },
  methods: {}
};
</script>

<style></style>
