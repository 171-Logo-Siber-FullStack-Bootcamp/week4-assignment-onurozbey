<template>
    <!-- Page Wrapper -->
    <div id="wrapper">
        <!-- Sidebar -->
        <AllSidebar />
        <AllContent />
    </div>
    <!-- End of Page Wrapper -->
</template>

<script>
import AllSidebar from "./SidebarComps/AllSidebar.vue"
import AllContent from "./ContentComps/AllContent.vue"
export default {
    name: "PageWrapper",
    components: { AllSidebar, AllContent }
}
</script>