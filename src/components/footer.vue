<template>
    <div class="footer-grid">
        <div></div>
        <h3>Email</h3>
        <h3>Phone</h3>
        <h3>Jobs</h3>
        <div></div>
    </div>
</template>

<script>
export default {
    name: "page-footer"
}
</script>

<style scoped>
    .footer-grid {
        display: grid;
        align-items: center;
        justify-items: center;
        grid-template-columns: 2fr 1fr 1fr 1fr 1fr;
    }
</style>