<template>
    <div class="main-container">
        <div
            class="projects"
            v-for="items in projectData.ProjectsArray"
            v-bind:key="items"
        >
            <h2>{{ items.Title }}</h2>
            <img :src="items.Image" alt="image" />
            <p>{{ items.About }}</p>
        </div>
    </div>
</template>

<script>
import jsonData from "../../projects.json";
export default {
    data() {
        return {
            projectData: jsonData,
        };
    },
};
</script>

<style></style>
