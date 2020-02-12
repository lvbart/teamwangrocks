<template>
  <div id="app">
    <nav-bar></nav-bar>
    <home :imgDetail="imgDetail"></home>
    
   
    
    
  </div>
</template>

<script>

import NavBar from './components/NavBar.vue'
import Home from './views/Home.vue'


export default {
  name: 'app',
  components: {
    
    NavBar,
    Home,
  },
  
  data: () => ({
    imgDetail: {
      imgUrl: 'https://img1.doubanio.com/view/photo/m/public/p2585603719.webp',
      imgTitle: 'DWAY!'
      
    }
  })
  
}
</script>

<style>

</style>
