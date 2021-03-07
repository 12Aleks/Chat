<template>

    <component :is="layout">
        <router-view/>
    </component>

</template>

<script>
    import MainLayout from "./layouts/MainLayout";

    export default {
        name: 'App',
        components: {
            MainLayout
        },
        computed: {
            layout() {
                return (this.$route.meta.layout || 'empty') + '-layout'
            }
        },
    }
</script>
<style>

</style>
