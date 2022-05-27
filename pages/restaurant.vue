<template>
  <main class="container resturant">
    <h1>Restaurant page</h1>
    <AppRestaurantInfo/>
  </main>
</template>

<script>
 import AppRestaurantInfo from '@/components/AppRestaurantInfo.vue';

 export default {
   components: {
     AppRestaurantInfo
   },
 };
</script>

<style lang="scss" scoped>

</style>
