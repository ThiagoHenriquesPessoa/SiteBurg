<template>
  <NavbarComponente/>
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
  }
}
</script>

<style>

</style>
