<template>
    <div id="main-banner">
        <h1>Make Your Burguer</h1>
    </div>
</template>

<script>
export default {
    name: "Banner"
}
</script>

<style scoped>
#main-banner {
    background-image: url('/public/img/burger.jpg');
    background-position: right bottom -180px;
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
}

#main-banner h1 {
    color: #fff;
    text-align: center;
    font-size: 60px;
    background-color: #222;
    padding: 20px 40px;
}

@media (max-width: 1061px) {
    #main-banner {
        background-position: right bottom;
    }
}
</style>