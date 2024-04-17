<template>
  <div>
    <HeaderComponent/>
    <JumbotronComponent/>
    <MainComponent/>
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import JumbotronComponent from './components/JumbotronComponent.vue';
import MainComponent from './components/MainComponent.vue';
  export default {
    name: 'App',
    components: {
      HeaderComponent,
      JumbotronComponent,
      MainComponent
    }
    
  }
</script>

<style lang="scss" scoped>

</style>