<template>
    <!-- Content Wrapper -->
    <div id="content-wrapper" class="d-flex flex-column">
        <!-- Main Content -->
        <div id="content">
            <!-- Topbar -->
            <AllTopbar />

            <!-- Begin Page Content -->
            <PageContent />
        </div>
        <!-- End of Main Content -->

        <!-- Footer -->
        <FooterContent />
    </div>
    <!-- End of Content Wrapper -->
</template>

<script>
import PageContent from "./PageContent.vue";
import FooterContent from "./FooterContent.vue";
import AllTopbar from "./TopbarComps/AllTopbar.vue";
export default {
    name: "AllContent",
    components: { PageContent, FooterContent, AllTopbar }
}
</script>