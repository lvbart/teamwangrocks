<template>

  
    <div class="grid grid-flow-row sm:grid-flow-col md:grid-flow-col-dense lg:grid-flow-row-dense xl:grid-flow-col bg-gray-200">
    
      <div class="mt-6 px-4 max-w-sm w-full lg:max-w-full lg:flex">
        <div class="pb-5/6">
          <img class="rounded-lg shadow-md" :src="imgDetail.mv.imgUrl">        
        </div> 

        <div class="px-2 py-2 bg-gray-600 items-center text-indigo-100 leading-none lg:rounded-full flex lg:inline-flex" role="alert">
        <span class="flex rounded-full bg-indigo-500 uppercase px-2 py-1 font-bold mr-3">{{imgDetail.mv.imgTitle}}</span>
        </div>
      </div>


      <div class="mt-6 px-4 max-w-sm w-full lg:max-w-full lg:flex">
        <div class="w-full">
          <img class="rounded-lg shadow-md" :src="imgDetail.ad.imgUrl">        
        </div> 

        <div class="p-2 bg-gray-600 items-center text-indigo-100 leading-none lg:rounded-full flex lg:inline-flex" role="alert">
        <span class="flex rounded-full bg-indigo-500 uppercase px-2 py-1 font-bold mr-3">{{imgDetail.ad.imgTitle}}</span>
        </div>
      </div>

      <div class="mt-6 px-4 max-w-sm w-full lg:max-w-full lg:flex">
        <div class="pb-5/6">
          <img class="rounded-lg shadow-md" :src="imgDetail.stage.imgUrl">        
        </div> 

        <div class="p-2 bg-gray-600 items-center text-indigo-100 leading-none lg:rounded-full flex lg:inline-flex" role="alert">
        <span class="flex rounded-full bg-indigo-500 uppercase px-2 py-1 font-bold mr-3">{{imgDetail.stage.imgTitle}}</span>
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