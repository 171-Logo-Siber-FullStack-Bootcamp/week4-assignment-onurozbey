<template>
    <!-- Topbar Navbar -->
    <ul class="navbar-nav ml-auto">
        <!-- Nav Item - Search Dropdown (Visible Only XS) -->
        <NavbarSearch />

        <!-- Nav Item - Alerts -->
        <NavbarAlerts />

        <!-- Nav Item - Messages -->
        <NavbarMessages />

        <div class="topbar-divider d-none d-sm-block"></div>

        <!-- Nav Item - User Information -->
        <NavbarUserInfo />
    </ul>
</template>

<script>
import NavbarSearch from "./TopbarNavbar/NavbarSearch.vue";
import NavbarAlerts from "./TopbarNavbar/NavbarAlerts.vue";
import NavbarMessages from "./TopbarNavbar/NavbarMessages.vue";
import NavbarUserInfo from "./TopbarNavbar/NavbarUserInfo.vue";
export default {
    name: "TopbarNavbar",
    components: { NavbarSearch, NavbarAlerts, NavbarMessages, NavbarUserInfo }
}
</script>
