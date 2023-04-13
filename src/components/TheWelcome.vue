<script setup>

</script>

<template>
  <div>
    <body>
      <article>
    <section class="text">
      <h2> Join the spiritual growth elevation.</h2>
    </section>

    <section class="women">
      <img src="../assets/IMG-20230202-WA0002.jpg">
    </section>

    <a href="./about" class="button">Enter</a>
  </article>
  </body>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Cinzel:wght@500&display=swap');

*{
    box-sizing: border-box;
    font-family:'Cinzel', serif; 
}

html, body {
    height:100vh;
}

body {
    margin:0;
    padding:0;
    display: flex;
    justify-content: center;
    align-items: center;
    /* background-color:#fbbc82; */
    background-color:hwb(60 75% 5%);
}

article {
    display: flex;
    flex-direction: column;
    justify-content: center;

}

.text {
    width: 90%;
    margin:0 auto;
    max-width: 1440px;
    text-align: center;
    background-image: linear-gradient(46deg,#503ab4 ,#dcf03d ,#ac2ee8 );
    font-size: 1.5rem;
    background-size: 200%;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: animate 15s linear infinite;
}

@keyframes animate {
    to {
      background-position: -200% ;
    }
} 

.women {
    display: flex;
    align-items: center;
    justify-content: center;
    width:100%;
    margin-top: 30px;

}
.women img {
    width: 70%;
    border-radius: 245px;
    border:2px solid #ffff004f;
    box-shadow: 0px 291px 231px 63px rgb(218 215 64 / 75%);
}
.button {
    border:1px solid #423eb9;
    border-radius: 40px;
    width:20%;
    margin:0 auto;
    color: #423eb9;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    font-size:1.2rem;
    cursor: pointer;
    margin-top: 80px;
}

.button:hover {
    color: #fafafa;
    border:1px solid #dcf03d;
    background-color:  #a5a3d7;
}

</style>

