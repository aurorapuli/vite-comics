<script>

export default {
    name: "Content",
}

</script>

<template>
    <main>
        <div class="jumbotron">
            <!-- <img src="../assets/images/jumbotron.jpg" alt="jumbotron"> -->

        </div>

        <h2 class="container">Content goes here</h2>
    </main>
</template>

<style lang="scss" scoped>
main {
    background-color: black;

    .jumbotron {
        height: 400px;
        background-image: url(../assets/images/jumbotron.jpg);
        background-size: cover;

    }

    h2 {
        padding: 40px 0;
        color: white;
    }
}
</style>
