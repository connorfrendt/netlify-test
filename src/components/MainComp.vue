<template>
    <div>
        This is the main component!
        THIS IS WORKING!!! :D
        <div id="press" @click="pressMe">PRESS ME!</div>
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
    display: inline-block;
}
</style>