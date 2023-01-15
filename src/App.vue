<template>
  <NavbarComponente :logo="logo_src" :alt="app_name"/>
  <router-view/>
  <FooterComponente/>
</template>
<script>
import NavbarComponente from './components/NavbarComponente.vue';
import FooterComponente from './components/FooterComponente.vue';
export default {
  name: "App",
  components:{
    NavbarComponente,
    FooterComponente
  },
  data(){
    return{
      logo_src: "./Img/logo.png",
      app_name: "Make your Burger"
    }
  }
}
</script>

<style>
*{
  font-family: Helvetica;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

.main-container{
  margin: 50px;
  min-height: 250px;
}

h1{
  text-align: center;
  font-size: 42px;
  margin-bottom: 30px;
  color: #222;
}
</style>
