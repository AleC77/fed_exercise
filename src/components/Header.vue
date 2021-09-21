<template>
  <nav>
    <Dropdown title="Home" :items="sublinks" />
    <Dropdown title="About" :items="sublinks" />
    <Dropdown title="Contact" :items="sublinks" />
    <Dropdown title="Privacy" :items="sublinks" />
  </nav>
</template>

<script>
import Dropdown from './Dropdown';
export default {
  name: 'navbar',
  components: {
    Dropdown
  },
  data () {
    return {
      sublinks: [
        {
          title: 'sublink1',
          link: '#'
        },
        {
          title: 'sublink2',
          link:'#'
        }
      ]
    }
  }
}
</script>

<style  lang="scss">
nav {
  position: absolute;
  top: 0.5em;
  left: 50%;
  transform: translate(-50%, 0);
  width:100%;
  max-width: 1234px;
  border-bottom:3px solid #dfdfdf;
  margin: 1em auto;
  display: inline-block;
  .menu-item {
    font-family: Avenir,Helvetica,Arial,sans-serif;
    font-size: 14px;
    padding: 2px 5px;
    cursor: pointer;
    display: inline-block;
    width:100px;
    color: #333;
    transition: 0.4s;
    &.active,
    &:hover {
      color: rgb(94, 94, 94);
    }
    a {
      color: inherit;
      text-decoration: none;
    }
  }
}
</style>
