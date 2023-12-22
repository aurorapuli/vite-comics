<script>

export default {
    name: "SignUp",
}

</script>

<template>
    <div class="sign-up">
        <div class="container">
            <a href="#">SIGN-UP NOW!</a>
            <div class="social">
                <p><strong>FOLLOW US</strong></p>
                <img src="../assets/images/footer-facebook.png" alt="Facebook">
                <img src="../assets/images/footer-twitter.png" alt="twitter">
                <img src="../assets/images/footer-youtube.png" alt="youtube">
                <img src="../assets/images/footer-pinterest.png" alt="pinterest">
                <img src="../assets/images/footer-periscope.png" alt="periscope">

            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/_mixins.scss' as *;
@use '../styles/partials/variables.scss' as *;

.sign-up {

    background-color: #222222;
    padding: 30px;
    color: $primary;

    div {
        @include flex('space-between');
        align-items: center;

        a {
            text-decoration: none;
            color: white;
            border: 1px solid $primary;
            padding: 5px;
        }

        .social {
            img {
                width: 25px;
                margin-left: 10px;
            }
        }

    }

}
</style>