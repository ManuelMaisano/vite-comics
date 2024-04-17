<template>
  <div>
    <HeaderComponent/>
    <JumbotronComponent/>
    <MainComponent/>
    <FooterTopComponent/>
    <FooterMidComponent/>
    <FooterBotComponent/>

  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import JumbotronComponent from './components/JumbotronComponent.vue';
import MainComponent from './components/MainComponent.vue';
import FooterTopComponent from './components/FooterTopComponent.vue';
import FooterMidComponent from './components/FooterMIdComponent.vue';
import FooterBotComponent from './components/FooterBotComponent.vue';
  export default {
    name: 'App',
    components: {
      HeaderComponent,
      JumbotronComponent,
      MainComponent,
      FooterTopComponent,
      FooterMidComponent,
      FooterBotComponent
    }
    
  }
</script>

<style lang="scss" scoped>

</style>