<template>
    <div id="app">
        <plug-in></plug-in>
    </div>
</template>

<script>
import PlugIn from './components/plugin.vue';
export default {
    name: 'app',
    data() {
        return {}
    },
    methods: {
    },
    components: {
        PlugIn,
    }
}
</script>

<style lang="scss">
body,
html {
    width: 100%;
    height: 100%;
    margin: 0;
    padding: 0;
}
#app {
    width: 100%;
    height: 100%;
    // background-color: #42b983;
    text-align: center;
}
</style>
