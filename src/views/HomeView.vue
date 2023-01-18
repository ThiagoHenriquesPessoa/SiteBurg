<template>
  <BannerComponente/>
  <div class="main-container">
    <h1>Monte o seu burger:</h1>
    <Formcomponete/>
  </div>
</template>

<script>
import BannerComponente from '@/components/BannerComponente.vue';
import Formcomponete from '@/components/Formcomponete.vue';



export default {
  name: 'HomeView',
  components: {
    BannerComponente,
    Formcomponete
}
}
</script>
