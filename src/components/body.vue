<template>
    <div class="body-grid">
        <side-panel/>
        <div id="body-content">
            <h2 id="body-title">Hey There!</h2>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quasi quae quis ipsam eveniet aliquam omnis nobis, temporibus minima blanditiis neque explicabo vitae unde necessitatibus dolore provident earum recusandae esse quisquam.</p>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quasi quae quis ipsam eveniet aliquam omnis nobis, temporibus minima blanditiis neque explicabo vitae unde necessitatibus dolore provident earum recusandae esse quisquam.</p>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quasi quae quis ipsam eveniet aliquam omnis nobis, temporibus minima blanditiis neque explicabo vitae unde necessitatibus dolore provident earum recusandae esse quisquam.</p>
        </div>
        <div></div>
        <tech-stack/>
        <div></div>
        <projects-page/>
    </div>
</template>

<script>
import SidePanel from "../components/side-panel.vue";
import TechStack from "../components/tech-stack.vue";
import ProjectsPage from "../components/projects.vue";

export default {
    name: "page-body",
    components: {
      SidePanel,
      TechStack,
      ProjectsPage
    }
}
</script>

<style scoped>
    .body-grid {
        display: grid;
        align-items: center;
        justify-items: center;
        grid-template-columns: 1fr 8fr;
    }

    #body-title {
        font-weight: bold;
        text-decoration: underline;
    }

    #body-content {
        font-size: 18px;
        margin: 2vw;
        border: 1px solid black;
        padding: 1vw;
    }

    p {
        text-align: justify;
    }
</style>