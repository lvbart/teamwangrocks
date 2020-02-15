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
      mv: {
        imgUrl: 'https://img1.doubanio.com/view/photo/m/public/p2585603719.webp',
        imgTitle: 'DWAY!'
      },
      ad: {
        imgUrl: 'https://img3.doubanio.com/view/photo/m/public/p2586104370.webp',
        imgTitle: 'Panda'
      },
      stage: {
        imgUrl: 'https://img3.doubanio.com/view/photo/m/public/p2586104390.webp',
        imgTitle: 'stage'
      }
      
      
    }
  })
  
}
</script>

<style>

</style>
