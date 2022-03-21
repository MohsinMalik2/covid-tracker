<template>
    <head-bar/>
    <div class="container mx-auto">
        <router-view/>
    </div>
</template>


<script>
import HeadBar from './components/HeadBar.vue';
export default{
   components: { HeadBar }, 
}
</script>
<style>

</style>
