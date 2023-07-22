<template>
    <div>
        This is the main component!
        THIS IS WORKING!!! :D
        <div id="press" v-bind:on-click="pressMe">PRESS ME!</div>
    </div>
</template>

<script>
export default {
    methods: {
        pressMe() {
            console.log('I am pressed!');
        }
    }
}
</script>

<style>
#press {
    background-color: red;
}
</style>