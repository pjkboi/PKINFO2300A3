<template>
  <div>
   <h1>Black Jack Counter App</h1>
   <h3>{{ counter }}</h3>
   <button class="button" @click="counter++">+</button>
   <button class="button" @click="counter--">-</button>
  </div>
</template>
<script>
export default {
 data(){
  return{
   counter: 0
  }
 }
 
}
</script>
<style scoped>
 .button{
    border: 2px solid black;
  background-color: white;
  color: black;
  padding: 14px 28px;
  font-size: 16px;
  cursor: pointer;
 }
</style>