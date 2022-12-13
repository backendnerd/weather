<template>
    <form action="" @submit.prevent="searchSubmit">
        <input
            placeholder="Another Location"
            type="text"
            name="cityTxt"
            id="cityTxt"
        />
        <button class="search" type="submit">
            <i class="fa-solid fa-magnifying-glass fa-2x"></i>
        </button>
    </form>
</template>

<script>
export default {};
</script>
<style scoped>
.search {
    border: 0;
    outline: none;
    padding: 1.5rem;
}
#cityTxt {
    border: 0;
    outline: none;
    padding: 2.25rem 0 0.75rem;
    margin: 0 3rem;
    background-color: transparent;
    width: 100%;
    color: #fff;
    border-bottom: 1px solid white;
}
#cityTxt::placeholder,
#cityTxt {
    font-size: 1.2rem;
}

#cityTxt::placeholder {
    color: #e0e0e0;
}
.search {
    background: yellow;
}
button {
    display: flex;
    align-items: center;
    justify-content: center;
}
form {
    display: flex;
    flex-direction: row;
}
</style>
