<template>
  <div>
    <nav class="uk-navbar-container" style="background-color: #ffffff">
      <div class="uk-container">
        <div uk-navbar>
          <div class="uk-navbar-left">
            <a class="uk-navbar-item uk-logo" href="#">
              <img
                :data-src="require('@/assets/images/logo/Rakitra JANGA.png')"
                width="80"
                alt=""
                uk-img
              />
            </a>
          </div>
          <div class="uk-navbar-right">
            <ul class="uk-navbar-nav">
              <li class="uk-active"><a href="#">Accueil</a></li>
              <li><a href="#">Article</a></li>
              <li><a href="#">FAQ</a></li>
              <li><a href="#">Contact</a></li>
            </ul>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>
