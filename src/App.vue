<template>
    <HeaderComponent />
    <MainComponent />
    <FooterOne />

</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue';
import FooterOne from './components/FooterOne.vue';
    export default {
        name:'App',
        components:{
            HeaderComponent,
            MainComponent,
            FooterOne
        },
        data(){
            return{

            }
        },
        methods:{

        }
      
    }
</script>

<style  scoped>


</style>