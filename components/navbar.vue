<template>
  <div>
    <!-- navbar -->
    <nav
      class="uk-navbar-container"
      style="background-color: #ffffff"
      uk-sticky
    >
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
          <!-- search form -->
          <!-- <div
            class="uk-navbar-center uk-hidden@m"
          >
            <form class="uk-search uk-search-default uk-width-1-1">
              <a href="" class="uk-search-icon-flip" uk-search-icon></a>
              <input
                class="uk-search-input custom-search-imput"
                type="search"
                placeholder="Recherche..."
              />
            </form>
          </div> -->

          <!-- //search form -->

          <div class="uk-navbar-right">
            <!-- search modal toggle -->
            <a
              class="uk-navbar-toggle uk-hidden@m"
              uk-search-icon
              uk-toggle="target: .nav-overlay; animation: uk-animation-fade"
              href="#"
            ></a>
            <!-- //search modal toggle -->

            <!-- right menu -->
            <ul class="uk-navbar-nav uk-visible@m">
              <li><nuxt-link to="/">Accueil</nuxt-link></li>
              <li><nuxt-link to="/article">Article</nuxt-link></li>
              <li><a href="#">FAQ</a></li>
              <li><nuxt-link to="/contact">Contact</nuxt-link></li>
            </ul>
            <!-- //right menu -->

            <!-- offcanvas toggle -->
            <a
              class="uk-navbar-toggle uk-hidden@m"
              uk-toggle="target: #offcanvas-nav"
            >
              <span uk-navbar-toggle-icon></span>
              <span class="uk-margin-small-left">Menu</span>
            </a>
            <!-- //offcanvas toggle -->
          </div>
        </div>
      </div>

      <!-- search modal -->
      <div class="nav-overlay uk-navbar-left uk-flex-1" hidden>
        <div class="uk-navbar-item uk-width-expand">
          <form class="uk-search uk-search-navbar uk-width-1-1">
            <a href="" class="uk-search-icon-flip" uk-search-icon></a>
            <input
              class="uk-search-input custom-search-imput"
              type="search"
              placeholder="Recherche..."
              autofocus
            />
          </form>
        </div>

        <a
          class="uk-navbar-toggle"
          uk-close
          uk-toggle="target: .nav-overlay; animation: uk-animation-fade"
          href="#"
        ></a>
      </div>
      <!-- //search modal -->
    </nav>
    <!-- //navbar -->

    <!-- //offcanvas -->
    <div
      id="offcanvas-nav"
      uk-offcanvas="overlay: true; flip: true; mode: push;"
    >
      <div class="uk-offcanvas-bar">
        <ul class="uk-nav uk-nav-default">
          <li><nuxt-link to="/">Accueil</nuxt-link></li>
          <li><nuxt-link to="/article">Article</nuxt-link></li>
          <li><a href="#">FAQ</a></li>
          <li><nuxt-link to="/contact">Contact</nuxt-link></li>
        </ul>
      </div>
    </div>
    <!-- //offcanvas -->
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>
