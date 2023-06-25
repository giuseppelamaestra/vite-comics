<template>
 <article>

    <h1>
        {{ ComicElement }}
    </h1>
 </article> 
 
</template>
<script>
export default {
    name : 'SingleComic',
    props: {
       ComicElement : Object,
    }
       
    
}
</script>

<style lang="scss" scoped>

article {
     width: calc(100% / 6);
}
</style>