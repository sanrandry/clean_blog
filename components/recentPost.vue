<template>
  <div class="uk-child-width-1-4" uk-grid>
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
