<template>
    <!-- Sidebar -->
    <ul class="navbar-nav bg-gradient-primary sidebar sidebar-dark accordion" id="accordionSidebar">
        <SidebarBrand />
        <SidebarNavItem />
        <SidebarAddons />
        <SidebarToggler />
    </ul>
    <!-- End of Sidebar -->
</template>

<script>
import SidebarBrand from "./SidebarBrand.vue";
import SidebarNavItem from "./SidebarNavItem.vue";
import SidebarAddons from "./SidebarAddons.vue";
import SidebarToggler from "./SidebarToggler.vue";
export default {
    name: "AllSidebar",
    components: { SidebarBrand, SidebarNavItem, SidebarAddons, SidebarToggler }
}
</script>