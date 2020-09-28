<template>
  <div class="">
    <navbar />
    <Nuxt />
    <app-footer />
  </div>
</template>

<script>
import navbar from "@/components/navbar";
import appFooter from "@/components/appFooter";
export default {
  components: {
    navbar: navbar,
    "app-footer": appFooter,
  },
};
</script>

<style>
</style>
