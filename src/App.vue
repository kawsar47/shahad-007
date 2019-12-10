<template>
  <div id="app">
 <Header></Header>
 <Slider></Slider>
 <Product></Product>
 <Newsletter></Newsletter>
 <Sponsor></Sponsor>
<Footer></Footer>
 
  </div>
</template>

<script>
import Header from './components/Header'
import Slider from './components/Slider'
import Product from './components/Product'
import Footer from './components/Footer'
import Newsletter from './components/Newsletter'
import Sponsor from './components/Sponsor'



 
export default {
  components: {
    Header,
    Slider,
    Product,
    Newsletter,
    Sponsor,
    Footer
    
  }
}
</script>

<style>
 
</style>
