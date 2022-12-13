<template>
    <div class="pannel">
        <CitySearch />
        <SuggestedCities />
        <WeatherDetails />
    </div>
</template>

<script>
import CitySearch from "./CitySearch.vue";
import SuggestedCities from "./SuggestedCities.vue";
import WeatherDetails from "./WeatherDetails.vue";
export default {
    components: {
        CitySearch,
        SuggestedCities,
        WeatherDetails,
    },
};
</script>
<style scoped>
.pannel {
    max-width: 500px;
    min-width: 450px;
    min-height: 100vh;
    background-color: #ccc;

    position: absolute;
    right: 0;
}
</style>
