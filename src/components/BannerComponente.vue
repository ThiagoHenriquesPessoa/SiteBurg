<template>
    <div id="main-banner">
     <h1>Make Your Burger</h1>
    </div>
  </template>
  
  <script>
  
  
  export default {
    name: 'BannerConponente'
  }
  </script>

  <style scoped>
  #main-banner {
    background-image: url('/public/Img/burger.jpg');
    background-position: 0 -300px;
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
  }

  #main-banner h1{
    color: #fff;
    text-align: center;
    font-size: 60px;
    padding: 20px;
  }
  </style>