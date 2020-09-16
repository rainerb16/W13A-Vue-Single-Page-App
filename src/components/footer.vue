<template>
    <div class="footer-grid">
        <h3>Email</h3>
        <h3>LinkedIn</h3>
        <h3>GitHub</h3>
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
        grid-template-columns: 1fr 1fr 1fr;
        margin: 1vw;
    }
</style>