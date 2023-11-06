<template>
  <div class="max-w-screen-xl mx-auto p-5 sm:p-10 md:p-16">

    <div>
      <PrimaryFilter/>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-3 sm:grid-cols-2 gap-10" v-for="(item , index) in tab" :key="index">
        
    </div>

</div>
</template>

<script setup lang="ts">
import PrimaryFilter from "../../components/formComponents/PrimaryFilter.vue";
import RestaurantCard from "../../components/pagesComponents/RestaurantCard.vue";

const tab = [1 , 2 , 3 , 4 , 5 , 6, 7, 8, 9 ,10]

</script>

<style scoped>

</style>