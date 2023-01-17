<template>
    <Footer id="footer">
        <p>
            Make your Burger &copy; 2023
        </p>
    </Footer>
  </template>
  
  <script>
  
  
  export default {
    name: 'FooterComponente',
    components: {
    }
  }
  </script>

  <style scoped>
  #footer {
    height: 100px;
    background-color: #222;
    border-top: 4px solid #111;
    color: #fcba03;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    /* position: absolute; */
	  bottom: 0;
  }
  </style>