<template>
    <section>
        <WeatherStatus class="status" />
        <DetailsPannel />
    </section>
</template>

<script>
import WeatherStatus from "./WeatherStatus.vue";
import DetailsPannel from "./DetailsPannel.vue";

export default {
    components: { WeatherStatus, DetailsPannel },
    date: () => {
        return {
            city: "London",
        };
    },
};
</script>
<style scoped>
section {
    display: flex;
}
.status {
    position: absolute;
    bottom: 128px;
    left: 128px;
}
</style>
