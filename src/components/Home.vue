<template>
  <main>
    <div><h1>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</h1></div>
    <div class="man">Fund Manager Webcast Series</div>
  </main>
</template>

<style  lang="scss" scoped>
  main{
    width:100%;
    max-width: 1234px;
    margin: 3em auto;
    display: grid;
    grid-template-columns: 60% 40%;
    h1{
      width: 605px;
      height: 272px;
      font-size: 72px;
      letter-spacing: 0px;
      line-height: 68px;
      color: #4a4a4a;
      font-weight: bold;
      font-family: "Linotype Univers",Helvetica,Arial,sans-serif;
      text-align: right;
    }
    div.man {
      width: 100%;
      writing-mode: vertical-rl;
      text-orientation: mixed;
      background: #f9f8f8 url('../assets/man.png') no-repeat center center;
      font-size: 12px;

    }
  }
</style>