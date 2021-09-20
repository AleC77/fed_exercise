<template>
  <nav>
    <ul>
      <li>Item1<i class="arrow down"></i></li>
      <li>Item2<i class="arrow down"></i></li>
      <li>Item3<i class="arrow down"></i></li>
      <li>Item4<i class="arrow down"></i></li>
    </ul>
  </nav>
</template>

<style  lang="scss" scoped>
  nav{
    width:100%;
    max-width: 1234px;
    border-bottom:3px solid #dfdfdf;
    margin: 3em auto;
  }

  ul {
    list-style: none;
    padding: 0;

    li {
      font-family: Avenir,Helvetica,Arial,sans-serif;
      font-size: 14px;
      padding: 2px 5px;
      cursor: pointer;
      display: inline-block;
      width:100px;
      color: #333;
      .arrow {
        border: solid #bb676c;
        border-width: 0 1px 1px 0;
        display: inline-block;
        padding: 3px;
        margin-left: 0.5em;
      }
      .down {
        transform: rotate(45deg);
        -webkit-transform: rotate(45deg);
      }
      &:hover {
        color: rgb(94, 94, 94);
      }
    }
  }
</style>
