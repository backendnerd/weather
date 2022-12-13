<template>
    <ul>
        <li v-for="city in cities" :key="city">{{ city }}</li>
    </ul>
</template>

<script>
export default {
    data() {
        return {
            cities: ["Marrakech", "Rabat", "Fes", "Tanger"],
        };
    },
};
</script>
<style scoped>
ul li {
    list-style: none;
}
</style>
