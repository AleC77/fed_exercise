<template>
 <div>
   <Header/>
   <Home/>
   <Footer/>
 </div>
</template>

<script>
  import Header from './components/Header'
  import Home from './components/Home'
  import Footer from './components/Footer'

  export default {
     components:{
         Header,
         Home,
         Footer
     }
  }
</script>

<style>
@font-face {
  font-family: 'Avenir';
  src: url('/assets/fonts/Avenir.eot?#iefix') format('embedded-opentype'),
  url('/assets/fonts/Avenir.woff') format('woff'),
  url('/assets/fonts/Avenir.woff2') format('woff2'),
  url('/assets/fonts/Avenir.ttf')  format('truetype');
}
  *{
      box-sizing:border-box;
      margin: 0 auto;
  }
  div {
    font-family: Helvetica, Arial, sans-serif;
    font-size: 18px;
    margin: 0 auto;
    background-color:#fff;
  }
</style>