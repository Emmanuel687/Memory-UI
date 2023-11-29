<template>
  <div class="main-page">
    <MemoryForm />
    <div class="memory">
      <MemoryList />


    </div>

  </div>


  

</template>

<script setup>
import MemoryForm from "./components/MemoryForm.vue";
import MemoryList from "./components/MemoryList.vue"
import Button from "primevue/button"

</script>

<style scoped>
.main-page{

border: 1px solid green;
padding: 20px;}
.memory{
  margin-top: 10px;


}

</style>