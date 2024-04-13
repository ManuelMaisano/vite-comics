<template>
    <HeaderComponent />
    <MainComponent />
    <FooterOne />
    <FooterTwo />

</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue';
import FooterOne from './components/FooterOne.vue';
import FooterTwo from './components/FooterTwo.vue';
    export default {
        name:'App',
        components:{
            HeaderComponent,
            MainComponent,
            FooterOne,
            FooterTwo
        },
        data(){
            return{

            }
        },
        methods:{

        }
      
    }
</script>

<style  lang="scss" scoped>


</style>