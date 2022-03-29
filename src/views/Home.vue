<template>
    <span>
        <home-hero></home-hero>
        <home-details></home-details>
        <home-plans></home-plans>
    </span>
</template>

<script>
//import HelloWorld from '../components/HelloWorld';
import HomeHero from '@/components/HomeHero';
import HomeDetails from '@/components/HomeDetails.vue';
import HomePlans from '@/components/HomePlans';

export default {
    name: 'Home',
    components: {
        HomeHero,
        HomeDetails,
        HomePlans,
    },
};
</script>
