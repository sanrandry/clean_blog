<template>
  <div
    class="uk-child-width-1-4@m"
    uk-grid
    uk-scrollspy="cls: uk-animation-fade; target: .uk-card; delay: 250;"
  >
    <post-card v-for="item in 8" />
  </div>
</template>

<script>
import postCard from "@/components/common/postCard";
export default {
  components: {
    "post-card": postCard,
  },
};
</script>

<style>
</style>
