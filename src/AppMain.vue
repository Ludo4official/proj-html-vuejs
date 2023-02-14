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

    <AppMainSectionOne></AppMainSectionOne>
    <AppMainSectionTwo class="mt-5"></AppMainSectionTwo>
    <AppMainSectionThree class="mt-5"></AppMainSectionThree>
    <AppMainSectionFour class="mt-5"></AppMainSectionFour>
    <AppMainSectionFive class="mt-5"></AppMainSectionFive>
    <AppMainSectionSix class="mt-5"></AppMainSectionSix>
    <AppMainNewsletter class="mt-5"></AppMainNewsletter>

</template>

<style lang="scss" scoped>

</style>
