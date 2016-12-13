<template>
<div id="app">
    <p>
        {{msg}}
    </p>
</div>
</template>

<script>
export default {
    data() {
        return {
            msg: 'Welcome to Your Vue.js App'
        }
    },
    components: {
    }
};
</script>

<style lang="stylus">
#app
    font-family: 'Avenir', Helvetica, Arial, sans-serif
    -webkit-font-smoothing: antialiased
    -moz-osx-font-smoothing: grayscale
    text-align: center
    color: #2c3e50
    margin-top: 60px
</style>
