<template>
  <footer>
    <form id="search-box">
      <input type="search" placeholder="Lorem ipsum...">
      <i class="fa fa-search"></i>
    </form>
  </footer>
</template>


<style lang="scss" scoped>
  footer{
    width:1234px;
    max-width:100%;
    height:100px;
    padding: 3em auto;
    margin-bottom: 1em;
    border-right:3px solid #dfdfdf;
    border-top:1px solid #dfdfdf;
    border-bottom:1px solid #dfdfdf;
    text-align: center;
    vertical-align: middle;
    form {
      margin: 25px auto;
    }

    input {

      outline: none;
      margin: auto;
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
    width: 90%;

    -moz-box-shadow: inset 0 7px 9px -7px rgba(0,0,0,0.4);
    -webkit-box-shadow: inset 0 7px 9px -7px rgba(0,0,0,0.4);
    box-shadow:inset 0 7px 9px -7px rgba(0,0,0,0.4);
    color: #333;
  }

  input:-moz-placeholder, input::-webkit-input-placeholder {
    color: #333;
  }
  }


</style>
