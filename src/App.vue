<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>

     <div class="container">
      <div class="row">
        <div class="col-md-4 log-school">
          My School
        </div>

        <div class="col-md-8">
          <ul class="text-right">
            <li> <RouterLink to="/" >Home</RouterLink></li>
            <li><RouterLink to="/about"  >About</RouterLink></li>
            <li> <RouterLink to="/admission" > Admission </RouterLink></li>
            <li><RouterLink to="/contact" >contact us</RouterLink></li>
     
          </ul>
        </div>
      </div>
        
      
     </div>

       
   
  </header>

  <RouterView />
  
</template>
<style lang="scss">
  header{
    background-color: #fdd31d;
    color: #fff;
    overflow: hidden;

  }
  a{
    text-decoration:none !important;
    color: #fff !important;
  }
  ul{
    padding: 20px;
    float: left;
    width: calc(100% );
    text-align: right;
  }
  li{
    display: inline;
    padding: 20px;
    font-size: 20px;
  }
  .log-school{
    font-size: 36px;
    font-family: emoji;
    padding-top: 9px;
  }
</style>


