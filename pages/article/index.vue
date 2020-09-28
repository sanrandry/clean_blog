<template>
  <div class="uk-container uk-section">
    <div uk-grid>
      <!-- left section -->
      <div class="uk-width-3-4@m uk-width-1-1">
        <div
          class="uk-child-width-1-3@m uk-child-width-1-1"
          uk-scrollspy="cls: uk-animation-fade; target: .uk-card; delay: 250;"
          uk-grid
        >
          <post-card v-for="item in 20" />
        </div>
      </div>
      <!-- //left section -->

      <!-- right section -->
      <div class="uk-width-1-4@m uk-width-1-1">
        <sidebar />
      </div>
      <!-- //right section -->
    </div>
  </div>
</template>

<script>
import postCard from "@/components/common/postCard";
import sidebar from "@/components/common/sidebar";
export default {
  components: {
    "post-card": postCard,
    sidebar: sidebar,
  },
};
</script>

<style>
</style>
