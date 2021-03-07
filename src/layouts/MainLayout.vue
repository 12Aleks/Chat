<template>
    <div class="container-fluid">
        <div class="row">
           <Navbar/>
           <Sidebar/>

            <main class="col-md-9 ms-sm-auto col-lg-10 px-md-4">
              <router-view></router-view>
            </main>
        </div>
    </div>
</template>

<script>
    import Navbar from "../components/Navbar";
    import Sidebar from "../components/Sidebar";
    export default {
        name: "MainLayout",
        components: {Sidebar, Navbar},
    }
</script>

<style scoped>

</style>