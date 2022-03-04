<template>
    <!-- Heading -->
    <div class="sidebar-heading">Addons</div>

    <!-- AddonsPages -->
    <AddonsPages />

    <!-- AddonsCharts -->
    <AddonsCharts />

    <!-- AddonsTables -->
    <AddonsTables />

    <!-- Divider -->
    <hr class="sidebar-divider d-none d-md-block" />
</template>

<script>
import AddonsPages from "./SidebarAddonsComps/AddonsPages.vue";
import AddonsCharts from "./SidebarAddonsComps/AddonsCharts.vue";
import AddonsTables from "./SidebarAddonsComps/AddonsTables.vue";
export default {
    name: "SidebarAddons",
    components: { AddonsPages, AddonsCharts, AddonsTables }
}
</script>