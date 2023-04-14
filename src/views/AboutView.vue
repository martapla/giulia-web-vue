<script setup>
import Navbar from '../components/Navbar.vue';
</script>

<template>
    <body>
      <Navbar />
      <div class="about">
         <h1>Hello, I'm Giulia! &#127904 <br>  A  passionate digital  artist! </h1>

         <h2>I create feminine <br>dreamy and mystical <br> ... experiences ...  <br>&#128150</h2>
      </div>
    </body>
</template>

<style scoped>

.about {
  min-height: 100%;
}
 .about h1{
    margin-top: 150px;
    display: flex;
    text-align: center;
    align-items: center;
    justify-content: center;
    color:rgb(118, 191, 215);
    line-height: 60px;
    word-spacing: 6px;
  }

  .about h2{
    margin-top: 70px;
    display: flex;
    text-align: center;
    justify-content: center;
    color:rgba(151, 52, 193, 0.727);
    line-height: 60px;
    font-size: 30px;
    word-spacing: 6px;
  }




</style>
