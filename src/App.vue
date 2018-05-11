<template>
  <div id="app">
    <Header></Header>
    <Banner></Banner>
    <Category></Category>
    <Product></Product>
  </div>
</template>



<script>
import Header from './components/header/header'
import Banner from './components/banner/banner'
import Category from './components/category/category'
import Product from './components/product/product'


export default {
  name: 'App',
  components: {
    Header,
    Banner,
    Category,
    Product
  }
}
</script>

<style>

#app {
  flex: 1;

}
.clearFix::before,
.clearFix::after{
    content: "";
    display: block;
    visibility: hidden;
    height: 0;
    line-height: 0;
    clear: both;
}

</style>
