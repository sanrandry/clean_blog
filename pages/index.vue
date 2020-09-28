<template>
  <div>
    <home-banner />
    <div class="uk-section">
      <div class="uk-container">
        <h2 class="uk-text-center">Article récent</h2>
        <recent-post />
      </div>
    </div>
    <contact-banner />
  </div>
</template>

<script>
import homeBanner from "@/components/homeBanner";
import recentPost from "@/components/recentPost";
import contactBanner from "@/components/contactBanner";
export default {
  components: {
    "home-banner": homeBanner,
    "recent-post": recentPost,
    "contact-banner": contactBanner,
  },
};
</script>

<style>
</style>
