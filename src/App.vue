<template>
  <div>
    <HeaderComponent/>
    <JumbotronComponent/>
    <MainComponent/>
    <FooterTopComponent/>
    <FooterMidComponent/>

  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import JumbotronComponent from './components/JumbotronComponent.vue';
import MainComponent from './components/MainComponent.vue';
import FooterTopComponent from './components/FooterTopComponent.vue';
import FooterMidComponent from './components/FooterMIdComponent.vue';
  export default {
    name: 'App',
    components: {
      HeaderComponent,
      JumbotronComponent,
      MainComponent,
      FooterTopComponent,
      FooterMidComponent,
    }
    
  }
</script>

<style lang="scss" scoped>

</style>