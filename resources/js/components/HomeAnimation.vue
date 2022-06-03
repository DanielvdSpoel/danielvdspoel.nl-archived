<template>
    <lottie :options="defaultOptions" height="100%" width="100%" />

</template>

<script>
import Lottie from './vendor/lottie'
import * as animationData from '../animations/coder.json';

export default {
    name: "HomeAnimation",
    components: {
        'lottie': Lottie
    },
    data() {
        return {
            defaultOptions: {animationData: animationData},
        }
    }
}
</script>

<style scoped>

</style>
