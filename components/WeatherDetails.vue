<template>
    <div class="details">
        <!-- This should be get as props {Key: Value} -->
        <ul>
            <li>Cloudy</li>
            <li>86%</li>
        </ul>
        <ul>
            <li>Humidity</li>
            <li>62%</li>
        </ul>
        <ul>
            <li>Wind</li>
            <li>8km/h</li>
        </ul>
    </div>
</template>

<script>
export default {
    data: () => {
        return {
            list: ["Cloudy", "Humidity", "Wind"],
        };
    },
};
</script>

<style scoped>
ul li {
    list-style: none;
}
</style>
