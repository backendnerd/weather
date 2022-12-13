<template>
    <WeatherApp />
</template>

<script>
import WeatherApp from "./components/WeatherApp.vue";

export default {
    name: "App",
    components: {
        WeatherApp,
    },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Rubik:wght@300;400;500&display=swap");
body {
    font-family: "Rubik", sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #121212;
    margin: 0;
    padding: 0;
    min-height: 100vh;
}
</style>
