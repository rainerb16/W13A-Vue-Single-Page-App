<template>
    <div class="header-grid">
        <img id="spock-hand" alt="Spock Hand" src="../assets/vulcan.png">
        <div></div>
        <h3>About Me</h3>
        <h3>Coding</h3>
        <h3>Music</h3>
    </div>
</template>


<script>
    export default {
        name: "page-header"
    }
</script>


<style scoped>
    .header-grid {
        display: grid;
        grid-template-columns: 1fr 2fr 1fr 1fr 1fr;
        justify-items: center;
        align-items: center;
    }

    #spock-hand {
        width: 60%;
    }
</style>