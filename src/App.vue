<script>
import AppTitleComponent from './components/AppTitle.vue';
import AppHeroComponent from './components/AppHero.vue';
export default {
    name:"Main",
    data(){
        return {
            
        }
    },
    methods:{

    },
    components:{
        AppTitleComponent,
        AppHeroComponent
    }
}
</script>
<template>

    <AppTitleComponent/>
    <AppHeroComponent/>
</template>