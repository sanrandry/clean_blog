<template>
  <div>
    <div
      class="uk-height-large uk-flex uk-flex-center uk-flex-middle uk-background-cover"
      :data-src="require('@/assets/images/home/pexels-trang-doan-1128678.jpg')"
      uk-img
    >
      <div
        class="uk-flex uk-light uk-flex-column uk-flex-center uk-flex-middle"
        style="width: 100%; height: 100%; background: rgb(0 173 239 / 15%)"
      >
        <h1 class="uk-animation-fade">Background Image</h1>
        <p class="uk-width-1-2@m uk-text-center uk-animation-fade">
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae
          eligendi laboriosam harum?
        </p>
        <div class="uk-width-1-2@m uk-visible@s">
          <search-form class="uk-animation-slide-top" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import searchForm from "@/components/common/searchForm";
export default {
  components: {
    "search-form": searchForm,
  },
};
</script>

<style>
</style>
