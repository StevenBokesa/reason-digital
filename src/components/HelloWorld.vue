<template>
    <div class="topBar">
      <div class="search"><i class="fas fa-search"></i>Search</div>
      <div class="buttons">
      
        <div class="learn">Learn</div>
        <div class="donate">Donate</div>
      
      </div>
    </div>
    <header>
    <img alt="Vue logo" src="../assets/logo.png" height="50">
    <nav>
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/about">What we do</router-link></li>
        <li><router-link to="/">The digital divide</router-link></li>
        <li><router-link to="/about">Get Involved</router-link></li>
        <li><router-link to="/">Our network</router-link></li>
        <li><router-link to="/about">Insights</router-link></li>
      </ul>
    </nav>
  </header>
  <div class="section-1">
    <img alt="banner image" src="../assets/banner.jpg" height="400px">
    <div class="item-1">
      <h1> Get online week 2021 </h1>
    </div>
    <div class="item-2">
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing<br>elit, sed do eiusmod tempor
         incididunt ut labore et<br> dolore magna aliqua.</p>
    </div>
    <div class="item-3">
      <Button text="Get involved now!" />
    </div>
    <div class="item-4">
     <div class="left-image">
     <img alt="small image" src="../assets/small.jpg" height="200px"> 
     </div>
     <div class="right-image">
     <h2> We are a social change charity,<br>
      helping people to improve their lives <br>
      through digital</h2>
      <p>We tackle the most pressing issues of our time, working<br>
      with partners in thousands of communities accross the UK<br>
      and further afield.</p>
      <ButtonTwo text="Add task" />
     </div>

    </div>
    <div class="item-5">
      <h2>How can we help you?</h2>
      <p>Let us know who you are and what you're looking for, and we'll help you get you in the right place.</p>
      <div class="dropdown">I am  an Individual and I want want to learn </div>
      
      
    </div>
    <div class="item-6">
      <h2>What do we do?</h2>
      <p>You might not have heard of us, but we're the people behind the following impactful programmes.</p>
      <div class="boxes">
      <div class="box-1">
        <Box title="Get online week" text="Lorem ipsum dolor imet" />
      </div>
      <div class="box-2">
        <Box title="Get online week" text="Lorem ipsum dolor imet" />
      </div>
      <div class="box-3">
        <Box title="Get online week" text="Lorem ipsum dolor imet" />
      </div>
      <div class="box-4">
        <Box title="Get online week" text="Lorem ipsum dolor imet" />
      </div>
      </div>
      <div class="btn-more">
      <Button text="More about what we do" />
      </div>  
    </div>
    
  </div>
</template>

<script>
import Button  from './Button.vue'
import ButtonTwo  from './ButtonTwo.vue'
import Box from './Box.vue'

export default {
  name: 'HelloWorld',
  components:{
    Button,
    ButtonTwo,
    Box,
   
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header {
    display: flex;
    border-bottom: 1px solid #ccc;
    padding: .5rem 1rem;

  }

   nav {
      margin-left: auto;
      margin-right: 35px;
    }
   nav ul {
      list-style: none;
    }

    nav ul li {
      display: inline-flex;
      margin-left: 1rem;
    }

    .topBar{
      display: flex; 
      padding: .5rem 1rem;
      margin-top: -15px;
      border-bottom: 1px solid #ccc;

    }

    .search{
      border-left: 1px solid #ccc;
      border-right: 1px solid #ccc;
      border-bottom: 1px solid #ccc;
      margin-left: 25px;
      padding-left: 15px;
      padding-right: 15px;
      padding-top: 20px;
      padding-bottom: 10px;
      margin-bottom: -9px;
    }

    .buttons{
      display: flex;   
      margin-left: auto;
    }

    header img{
      margin-left: 35px;
    }

    .learn {
      border-left: 1px solid #ccc;
      border-right: 1px solid #ccc;
      border-bottom: 4px solid #2eab9e;
      padding-top: 15px ;
      padding-left: 15px;
      padding-right: 15px; 
      margin-bottom: -9px;
      
    }

    .donate {
      border-right: 1px solid #ccc;
      padding-top: 15px ;
      padding-left: 15px;
      padding-right: 15px; 
      margin-bottom: -9px;
      margin-right: 35px;
      background-color:#c41247;
      color: #fff;
      font-weight: bold;
    }

    .section-1 img{
      position: relative;
      height:400px;
      width: 100%;
      
    }

    .item-1{
      position: absolute;
      top: 150px;
      left: 50px;
      background-color:#2e94b0;
      padding-left: 15px;
      padding-right: 15px;
      color: #fff; 
    }

    .item-2{
      position: absolute;
      top: 250px;
      left: 50px;
      background-color:#fff;
      padding-left: 15px;
      padding-right: 15px;
      color: #fff; 
      text-align: left;
      color: #2eab9e;
    }

    .item-3{
      position: absolute;
      top: 400px;
      left: 50px;
      
    }

    .item-4{
      margin-top: -4px;
    }

    
    .left-image{
      width: 625px;
      float: left;
    }

    .right-image{
      overflow: hidden;
      background-color: #2eab9e;
      height: 450px;
    }

    .right-image h2{
      text-align: left;
      margin-top: 50px;
      margin-left: 50px;
      color: #fff;
    }

    .right-image p{
      text-align: left;
      margin-top: 50px;
      margin-left: 50px;
      color: #fff;
    }

    .item-5{
      background-color: #dedcdc;
      margin-top: -50px;
      height: 350px;
    }
    .item-5 h2{
      text-align: left;
      margin-left: 50px;
      margin-top: 50px;
      position: absolute;
    }

    .item-5 p{
      position: absolute;
      text-align: left;
      margin-left: 50px;
      top: 1000px;
    }

    .dropdown{
      background-color: #fff;
      position: absolute;
      top: 1075px;
      left: 200px;
      padding: 50px 300px;
    }

    .item-6 {
      background-color: #2e94b0;
      margin-top: -20px;
      height: 500px;
    }

    .item-6 h2{
      text-align: left;
      padding-top: 50px;
      padding-left: 50px;
      color: #fff;
    }

    .item-6 p{
      text-align: left;
      padding-left: 50px;
      color: #fff;  
    }

    .boxes{
      display: flex;
    }
    .box-1{
      background-color: #fff;
      width: 200px;
      height:250px;
      margin-left: 50px;
      
    }

    .box-2{
      background-color: #fff;
      width: 200px;
      height:250px;
      margin-left: 100px;  
    }

    .box-3{
      background-color: #fff;
      width: 200px;
      height:250px;
      margin-left: 100px;  
    }

    .box-4{
      background-color: #fff;
      width: 200px;
      height:250px;
      margin-left: 100px;  
    }

    .btn-more{
      margin-top: 40px;
      margin-right: 40px;
    }
    



</style>
