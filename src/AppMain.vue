<script>
import AppMainSectionOne from './AppMainSectionOne.vue';
import AppMainSectionTwo from './AppMainSectionTwo.vue';
import AppMainSectionThree from './AppMainSectionThree.vue';
import AppMainSectionFour from './AppMainSectionFour.vue';
import AppMainSectionFive from './AppMainSectionFive.vue';
import AppMainSectionSix from './AppMainSectionSix.vue';
import AppMainNewsletter from './AppMainNewsletter.vue';
export default {
    name: 'AppMain',
    components: {
        AppMainSectionOne,
        AppMainSectionTwo,
        AppMainSectionThree,
        AppMainSectionFour,
        AppMainSectionFive,
        AppMainSectionSix,
        AppMainNewsletter,
    }
}
</script>

<template>

    <div class="container">
        <AppMainSectionOne></AppMainSectionOne>
        <AppMainSectionTwo></AppMainSectionTwo>
        <AppMainSectionThree ></AppMainSectionThree>
        <AppMainSectionFour></AppMainSectionFour>
        <AppMainSectionFive></AppMainSectionFive>
    </div>

    <AppMainSectionSix></AppMainSectionSix>

    <div class="container">
        <AppMainNewsletter></AppMainNewsletter>
    </div>

</template>

<style lang="scss" scoped>

</style>
