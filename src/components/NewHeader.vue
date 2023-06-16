<template>


   
 <nav class="bg-white">
   <div class="wrapper flex space-between">
       
      <img src="../../public/imgs/dc-logo.png" alt="logo DC-comics">
      
       <ul class="flex header-link">
         <li v-for="link in links">
            {{ link }}
         </li>
        
   
     </ul>
   </div>
  </nav>


</template>
<script>
 export default {
   data(){
      return {  
         
         links : [
         'carachters',
         'comics',
         'movies',
         'tv',
         'games',
         'collectibles',
         'videos',
         'fans',
         'news',
         'shop',
      ],
   }
   
   }
 }
</script>

<style>

</style>