<template>
  <div class="">
    <navbar />
    <div style="min-height: 90vh">
      <Nuxt />
    </div>
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
