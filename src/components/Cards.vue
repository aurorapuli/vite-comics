<script>


export default {
    name: "Cards",
    props: {
        comics: Array
    }
}

</script>

<template>
    <div class="row">
        <div class="card" v-for="(card, i) in comics" :key="i">
            <img :src="card.thumb" :alt="card.series">
            <p>{{ card.series }}</p>

        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/_variables.scss' as *;

.row {
    margin-top: 30px;
    display: flex;
    flex-wrap: wrap;

    .card {
        width: calc((100% / 6) - 10px);
        margin: 0 5px;
        margin-bottom: 40px;

        img {
            margin-bottom: 8px;
        }
    }
}
</style>
