<template>
    <footer>
        <div class="wrapper footer-links flex">
          <div>
            <ul v-for="link in links">
              
              
              <li> 
                  {{ link }}
              </li>
            
           </ul>
          </div> 
      
          <div>
            <ul v-for="link in links">
              
              
              <li> 
                  {{ link }}
              </li>
            
           </ul>
          </div> 

          <div>
            <ul v-for="link in links">
              
              
              <li> 
                  {{ link }}
              </li>
            
           </ul>
          </div> 
        </div>
    </footer>
</template>
<script>
export default {
  name: 'NewFooter',
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
<style></style>