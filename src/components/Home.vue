<template>
  <main>
    <div class="mainTitle"><h1>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</h1></div>
    <div class="man">Fund Manager Webcast Series</div>
  </main>
</template>

<style  lang="scss" scoped>
  main{
    width: 1234px;
    max-width: 100%;
    margin: 3em auto 0em auto;
    display: flex;
    justify-content: flex-end;
    align-items: center;
    background: #fff url('../assets/man.png') no-repeat 80% top;
    div.mainTitle{
      height: 488px;
      width: 100%;
      background: transparent;
      text-align:left;
      display:table;
      h1{
        color: #4a4a4a;
        font-weight: bold;
        font-family: "Linotype Univers",Helvetica,Arial,sans-serif;
        text-align: right;
        display:table-cell;
        vertical-align:middle;
        font-size: 72px;
        letter-spacing: 0px;
        line-height: 68px;
        padding-right: 50%;
        @media only screen and (max-width: 1020px) {
          /* For tablets: */
          font-size: 55px;
          letter-spacing: 0px;
          line-height: 50px;
          padding-right: 50%;
        }
        @media only screen and (max-width: 768px) {
          /* For mobile phones: */
          font-size: 55px;
          letter-spacing: 0px;
          line-height: 50px;
          padding-right: 10%;
        }
      }
    }
    div.man {
      width: 10px;
      writing-mode: vertical-rl;
      margin: 0px;
      text-align: center;
      font-size: 12px;
      background: transparent;
    }
  }
</style>