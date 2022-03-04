<template>
    <!-- Nav Item - Dashboard -->
    <li class="nav-item">
        <a class="nav-link" href="index.html">
            <i class="fas fa-fw fa-tachometer-alt"></i>
            <span>Onur Özbey - Dashboard</span>
        </a>
    </li>

    <!-- Divider -->
    <hr class="sidebar-divider" />
    <!-- Heading -->
    <div class="sidebar-heading">Interface</div>

    <!-- NavItemComponents -->
    <NavItemComponents />

    <!-- NavItemUtilities -->
    <NavItemUtilities />

    <!-- Divider -->
    <hr class="sidebar-divider" />
</template>

<script>
import NavItemComponents from "./SidebarNavItemComps/NavItemComponents.vue";
import NavItemUtilities from "./SidebarNavItemComps/NavItemUtilities.vue";
export default {
    name: "SidebarNavItem",
    components: { NavItemComponents, NavItemUtilities }
}
</script>