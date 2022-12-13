<template>
    <div class="status">
        <div class="temp">16°</div>
        <div class="location">
            <h1 class="city">London</h1>
            <p class="date">06:09 Monday, 12 Dec 2022</p>
        </div>
        <div class="icon">
            <i class="fa-solid fa-cloud fa-2x"></i>
            <p class="extra">Cloudy</p>
        </div>
    </div>
</template>

<script>
export default {};
</script>
<style scoped>
.status {
    display: flex;
}
.temp {
    font-size: 76px;
    margin: -0.5rem 0;
    font-weight: 400;
}
.location {
    display: flex;
    flex-direction: column;
}
.city {
    font-size: 40px;
    font-weight: 500;
}
.date,
.city,
.extra {
    margin: 0;
    padding: 0;
}
.icon {
    position: absolute;
    bottom: 0;
    right: 0;
    transform: translate(150%, -8px);
    text-align: center;
}
.icon,
.location {
    margin: 0 0.5rem;
}
</style>
