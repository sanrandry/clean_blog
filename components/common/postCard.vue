<template>
  <nuxt-link to="/article/single" class="linked-card">
    <div class="uk-card uk-card-default" style="cursor: pointer">
      <div class="uk-card-media-top">
        <img :data-src="require('@/assets/images/dummy.jpg')" uk-img alt="" />
      </div>
      <div class="uk-card-body">
        <p class="">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt
        </p>
      </div>
    </div>
  </nuxt-link>
</template>

<script>
export default {};
</script>

<style>
.linked-card:hover {
  text-decoration: none;
}
</style>
