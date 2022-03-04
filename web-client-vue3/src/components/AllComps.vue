<template>
    <div class="page-top">
        <PageWrapper />
        <ScrollTop />
        <LogoutModal />
    </div>
</template>

<script>
import PageWrapper from "./template/PageWrapper.vue"
import ScrollTop from "./template/ScrollTop.vue"
import LogoutModal from "./template/LogoutModal.vue"
export default {
    name: "AllComps",
    components: { PageWrapper, ScrollTop, LogoutModal }
}
</script>