<template>
  <footer>
    <form id="search-box">
      <input type="search" placeholder="Lorem ipsum...">
      <i class="fa fa-search"></i>
    </form>
  </footer>
</template>


<style  scoped>
  footer{
    width:100%;
    max-width: 1234px;
    margin: 3em auto;
  }
  input {
    outline: none;
    margin: 0 auto;
  }
  input[type=search] {
    -webkit-appearance: textfield;
    font-family: inherit;
    font-size: 100%;
  }
  input::-webkit-search-decoration,
  input::-webkit-search-cancel-button {
    display: none;
  }

  input[type=search] {
    background: #f9f8f8 url('../assets/search-icon.png') no-repeat right center;
    border: solid 1px #ccc;
    padding: 9px 10px 9px 32px;
    width: 1140px;
    -moz-box-shadow: inset 0 7px 9px -7px rgba(0,0,0,0.4);
    -webkit-box-shadow: inset 0 7px 9px -7px rgba(0,0,0,0.4);
    box-shadow:inset 0 7px 9px -7px rgba(0,0,0,0.4);
    color: #ababab;
  }

  input:-moz-placeholder, input::-webkit-input-placeholder {
    color: #ababab;
  }

</style>
