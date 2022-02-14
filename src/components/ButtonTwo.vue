<template>
    <button class="btn-2">{{text}}</button>
</template>

<script>

export default {
    name: 'ButtonTwo',
    props:{
        text:String,
    }
}
</script>

<style scoped>
 .btn-2{
  background-color: transparent;
  background-repeat: no-repeat;
  padding: 15px 25px;
  border-radius: 25px;
  border: 2px solid #fff;
  color: #fff;
  float: left;
  margin-left: 50px;
  margin-top: 30px;
 
 }
</style>
