<template>
  <div class="uk-container uk-section">
    <div uk-grid>
      <!-- left section -->
      <div class="uk-width-3-4@m uk-width-1-1">
        <h1>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</h1>
        <div>
          <p v-for="item in 5">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Inventore,
            nesciunt! Eaque possimus molestias est debitis facilis odio adipisci
            aliquam dolores, modi quod deserunt nulla deleniti eligendi, minima,
            quos asperiores quaerat.
          </p>
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
