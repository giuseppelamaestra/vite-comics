<template>
 
 <section class="bg-black">
  <div class="wrapper">
    <h1>
       Comics :
    </h1>
    <ComicsList/>

  </div>
  
</section>
</template>
<script>
import ComicsList from './ComicsList.vue'

export default {
  name: 'NewMain',
  components: {
    ComicsList,
  }
}
</script>
<style></style>