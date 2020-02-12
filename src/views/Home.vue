<template>

  
    <div class="border-r border-b border-l border-gray-400 lg:border-l-0 lg:border-t lg:border-gray-400 bg-white rounded-b lg:rounded-b-none lg:rounded-r p-4 flex flex-col justify-between leading-normal">
    <h1>Home</h1>
    <div class="max-w-sm w-full lg:max-w-full lg:flex">
      <div class="pb-5/6">
        <img class="h-full rounded-lg shadow-md" :src="imgDetail.imgUrl">        
      </div> 

      <div class="p-2 bg-indigo-800 items-center text-indigo-100 leading-none lg:rounded-full flex lg:inline-flex" role="alert">
      <span class="flex rounded-full bg-indigo-500 uppercase px-2 py-1 font-bold mr-3">{{imgDetail.imgTitle}}</span>
      </div>
   </div>
    </div>
    


  
</template>

<script>


export default {
  name: 'Home',
  components: {
    
  },
  props: ['imgDetail'],
}
  

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

</style>