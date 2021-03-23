<template>
    <div class="container-fluid">
        <div class="row">
            <main class="col-md-9 ms-sm-auto col-lg-10 px-md-4">
              <router-view></router-view>
            </main>
        </div>
    </div>
</template>

<script>
    export default {
        name: "MainLayout",
    }
</script>

<style scoped>

</style>