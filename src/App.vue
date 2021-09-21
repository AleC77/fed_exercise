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
  src: url('/assets/fonts/aveni_ff/Avenir.eot?#iefix') format('embedded-opentype'),
  url('/assets/fonts/aveni_ff/Avenir.woff') format('woff'),
  url('/assets/fonts/aveni_ff/Avenir.woff2') format('woff2'),
  url('/assets/fonts/aveni_ff/Avenir.ttf')  format('truetype');
  font-family: 'Linotype Univers';
  src: url('/assets/fonts/linotypeunivers-basicregular.eot?#iefix') format('embedded-opentype');
}
  *{
      box-sizing:border-box;
      margin: 0 auto;
  }
  div {
    width:100%;
    font-family: Helvetica, Arial, sans-serif;
    font-size: 18px;
    margin: 0;
    padding: 0;
    background-color:#fff;
  }
</style>