<template>
  <div>
    <div class="uk-margin">
      <form class="uk-search uk-search-default uk-width-1-1">
        <a href="" class="uk-search-icon-flip" uk-search-icon></a>
        <input
          class="uk-search-input custom-search-imput"
          type="search"
          placeholder="Recherche..."
        />
      </form>
    </div>
    <div class="uk-margin-small-left">
      <span>Categories</span>
      <div>
        <ul class="uk-nav uk-nav-default">
          <li><a href="#">Item</a></li>
          <li><a href="#">Item</a></li>
          <li class="uk-nav-divider"></li>
          <li><a href="#">Item</a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.custom-search-imput {
  transition: 0.2s;
  padding-left: 12px !important;
  border-radius: 50px;
}
.custom-search-imput:focus {
  border-color: #d74d02;
}
</style>
