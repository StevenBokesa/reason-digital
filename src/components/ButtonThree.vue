<template>
    <button class="btn-3">Read more</button>
</template>

<script>

export default {
    name: 'ButtonThree',
    props:{
        text:String,
    }
}
</script>

<style scoped>
 .btn-3{
  background-color: transparent;
  background-repeat: no-repeat;
  padding: 15px 25px;
  border-radius: 25px;
  border: 2px solid #000;
  color: #c41247;
  float: left;
  margin-left: 50px;
  margin-top: 30px;
  
 
 }
</style>
