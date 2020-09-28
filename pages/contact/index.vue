<template>
  <div class="uk-container">
    <div class="uk-section">
      <h1 class="uk-text-center">Contact</h1>
      <p class="uk-text-lead uk-text-center">
        Nous sommes très heureux d'avoir de vos nouvelles !
      </p>
      <p class="uk-text-center">
        Utilisez le formulaire ci-dessous pour nous contacter et nous ferons en
        sorte de vous répondre le plus rapidement possible !
      </p>
    </div>
    <div class="">
      <form action="" class="uk-form-stacked">
        <div
          class="uk-margin-auto uk-width-1-2@m uk-width-1-1 uk-margin-small-bottom"
        >
          <label class="uk-form-label" for="name">Nom</label>
          <div class="uk-form-controls">
            <input
              class="uk-input"
              id="name"
              type="email"
              placeholder="Votre nom..."
            />
          </div>
        </div>
        <div
          class="uk-margin-auto uk-margin-small-bottom uk-width-1-2@m uk-width-1-1"
        >
          <label class="uk-form-label" for="email">Email</label>
          <div class="uk-form-controls">
            <input
              class="uk-input"
              id="email"
              type="email"
              placeholder="Votre email..."
            />
          </div>
        </div>
        <div class="uk-margin-auto uk-width-1-2@m uk-width-1-1">
          <label class="uk-form-label" for="email">Message</label>
          <div class="uk-form-controls">
            <div class="uk-margin">
              <textarea
                class="uk-textarea"
                rows="5"
                placeholder="Votre message..."
              ></textarea>
            </div>
          </div>
        </div>
        <div class="uk-width-1-2@m uk-width-1-1 uk-margin-auto uk-text-right">
          <button
            class="uk-button uk-button-primary"
            style="border-radius: 30px"
          >
            Contactez-nous
          </button>
        </div>
      </form>
    </div>
    <div
      class="uk-width-1-2@m uk-width-1-1 uk-margin-auto uk-margin-medium-top"
    >
      <div uk-grid>
        <div class="uk-width-1-2">
          <span uk-icon="icon: mail"></span> rakitra@rakitra.mg
        </div>
        <div class="uk-width-1-2">
          <span uk-icon="icon:  receiver"></span> +261 32 79 123 18
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>
