<script>
import AppHeader from './AppHeader.vue';
import AppMain from './AppMain.vue';
import AppFooter from './AppFooter.vue';

export default {

    name:'App',
    components: {

        AppHeader,
        AppMain,
        AppFooter
    },

    data() {
        return {
        }
    }
}

</script>

<template>

 <AppHeader></AppHeader>

 
<AppMain></AppMain>
 
 
 <div class="container">
    <AppFooter></AppFooter>
 </div>
 
</template>

<style lang="scss">
@import './components/styles/main.scss';
</style>
