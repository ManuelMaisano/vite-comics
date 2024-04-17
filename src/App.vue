<template>
  <div>
    <HeaderComponent/>
    <JumbotronComponent/>
    <MainComponent/>
    <FooterTop/>

  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import JumbotronComponent from './components/JumbotronComponent.vue';
import MainComponent from './components/MainComponent.vue';
import FooterTop from './components/FooterTop.vue'
  export default {
    name: 'App',
    components: {
      HeaderComponent,
      JumbotronComponent,
      MainComponent,
      FooterTop,
    }
    
  }
</script>

<style lang="scss" scoped>

</style>