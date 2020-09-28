<template>
  <div id="search_container">
    <input id="search_input" style="height: 45px; width: 500px" />
    <a href="#" style="color: #d74d02" uk-icon="icon: search"> </a>
  </div>
</template>

<script>
/**
 * usage:
 * <search-form v-model="value" @click:append=""></search-form>
 */
export default {};
</script>

<style>
#search_container {
  display: flex;
  align-items: center;
  padding: 0px 20px 0px 20px;
  margin: 0 auto;
  width: 100%;
  border-radius: 30px;
  background-color: white;
  border: 1px solid #dcdcdc;
}
#search_container:hover {
  box-shadow: 1px 1px 8px 1px #dcdcdc;
}
#search_container:focus-within {
  box-shadow: 1px 1px 8px 1px #dcdcdc;
  outline: none;
}
#search_input {
  border: none;
  flex-grow: 1;
  font-size: 16px;
  outline: none;
}
.search_form__append {
  height: 20px;
}
</style>
