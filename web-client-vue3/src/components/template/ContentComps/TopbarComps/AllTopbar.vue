<template>
    <!-- Topbar -->
    <nav class="navbar navbar-expand navbar-light bg-white topbar mb-4 static-top shadow">
        <!-- Sidebar Toggle (Topbar) -->
        <TopbarSidebarToggler />

        <!-- Topbar Search -->
        <TopbarSearch />

        <!-- Topbar Navbar -->
        <TopbarNavbar />
    </nav>
    <!-- End of Topbar -->
</template>

<script>
import TopbarSearch from "./TopbarSearch.vue"
import TopbarNavbar from "./TopbarNavbar.vue"
import TopbarSidebarToggler from "./TopbarSidebarToggler.vue"
export default {
    name: "AllTopbar",
    components: { TopbarSearch, TopbarNavbar, TopbarSidebarToggler }
}
</script>