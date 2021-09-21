<template>
  <div class="menu-item" @click="isOpen = !isOpen">
    <a href="#">
      {{ title }}<i class="arrow down"></i>
    </a>
    <div class="sub-menu" v-if="isOpen">
      <div v-for="(item, i) in items" :key="i" class="menu-item">
        <a :href="item.link">{{ item.title }}</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'dropdown',
  props: ['title', 'items'],
  data () {
    return {
      isOpen: false
    }
  }
}
</script>

<style  lang="scss">
nav{
  .menu-item {
    .sub-menu {
      position: absolute;
      top: 1.5em;
      font-family: Avenir,Helvetica,Arial,sans-serif;
      font-size: 14px;
      padding: 2px 5px;
      cursor: pointer;
      display: block;
      width:100px;
      color: #333;
      transition: 0.4s;
      border:2px solid #dfdfdf;
      .menu-item {
        width:80px;
      }
    }
  }
}
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
</style>