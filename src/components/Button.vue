<template>
    <button class="btn">{{text}}</button>
</template>

<script>

export default {
    name: 'Button',
    props:{
        text:String,
    }
}
</script>

<style scoped>
 .btn{
  background-color: white;
  padding: 15px 25px;
  border-radius: 25px;
  color:#c41247;
  font-weight: bold;
  border: none;
  outline: none;
 
 }
</style>
