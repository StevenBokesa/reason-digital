<template>
    <h3 class="title-1">{{title}}</h3>
    <p class="text">{{text}}</p>
    <ButtonThree />

</template>

<script>
import ButtonThree  from './ButtonThree.vue'

export default {
    name: 'Box',
    props:{
        title:String,
        text:String,
    },
    components:{
    ButtonThree,
   
  }
}
</script>

<style scoped>
 .title-1 {
  padding-top: 30px;
  padding-bottom:5px;
  color:#000;
 }
</style>