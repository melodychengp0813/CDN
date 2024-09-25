<script setup>
import {ref} from 'vue'
    const num = ref(2);
           function clickMe(){
            num.value++
           }
            //console.log(num.value);
            //setInterval(() =>{
              //  num.value++
            //},1000);

           
</script>

<template>
  <div id="app">
     {{ num }}
     <button type="button" @click="clickMe">ClickMe!!!</button>
  </div>
</template>

<style scoped>

</style>
