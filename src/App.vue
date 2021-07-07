<template>
  <div id="app">
    <Headerlink/>
    <main>
      <Products/>
    </main>

    <Footer/>
   
  </div>
</template>

<script>
 
 import Products from './components/Products.vue'
 import Footer from './components/Footer.vue'
 import Headerlink from './components/headerlink.vue'

export default {
  name: 'App',
  components: {
    Products,
    Footer,
    Headerlink
  }
}
</script>

<style lang="scss">
// #app {
//   font-family: Avenir, Helvetica, Arial, sans-serif;
//   -webkit-font-smoothing: antialiased;
//   -moz-osx-font-smoothing: grayscale;
//   text-align: center;

// }
</style>
