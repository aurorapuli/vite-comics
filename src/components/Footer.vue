<script>

export default {
    name: "Footer",
}

</script>

<template>
    <section class="up">
        <div class="container">
            <div class="card">
                <div>
                    <img src="../assets/images/buy-comics-digital-comics.png" alt="">
                </div>
                <P>DIGITAL COMICS</P>
            </div>
            <div class="card">
                <div>
                    <img src="../assets/images/buy-comics-merchandise.png" alt="">
                </div>
                <P>DIGITAL COMICS</P>
            </div>
            <div class="card">
                <div>
                    <img src="../assets/images/buy-comics-subscriptions.png" alt="">
                </div>
                <P>DIGITAL COMICS</P>
            </div>
            <div class="card">
                <div>
                    <img src="../assets/images/buy-comics-shop-locator.png" alt="">
                </div>
                <P>DIGITAL COMICS</P>
            </div>
            <div class="card">
                <div>
                    <img src="../assets/images/buy-comics-shop-locator.png" alt="">
                </div>
                <P>DIGITAL COMICS</P>
            </div>
        </div>

    </section>
    <section class="down">
        <div class="container">
            <div>
                <div>
                    <ul>
                        <h4>DC COMICS</h4>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                    </ul>
                    <ul>
                        <h4>SHOP</h4>
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop DC Collection</a></li>

                    </ul>

                </div>
                <div>
                    <ul>
                        <h4>DC</h4>
                        <li><a href="#">Temes Of Use</a></li>
                        <li><a href="#">Privacy policy(New)</a></li>
                        <li><a href="#">Ad Choise</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">jobs</a></li>
                        <li><a href="#">Subscription</a></li>
                        <li><a href="#">Talent Workshops</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>

                </div>
                <div>
                    <ul>
                        <h4>DC</h4>
                        <li><a href="#">DC</a></li>
                        <li><a href="#"> MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>

                </div>

            </div>
            <div class="img">
                <img src="../assets/images/dc-logo-bg.png" alt="">
            </div>

        </div>

    </section>
</template>

<style lang="scss" scoped>
@use '../styles/partials/_mixins.scss' as *;
@use '../styles/partials/_variables.scss' as *;

.up {
    background-color: $primary;
    font-size: 10px;
    color: white;
    padding: 40px;

    div {
        @include flex('space-around');

        .card {
            display: flex;
            align-items: center;

            div {
                width: 35px;
                padding-right: 10px;
            }
        }

    }
}

.down {
    background-image: url(../assets/images/footer-bg.jpg);

    .container {

        @include flex('space-between');
        align-items: center;


        div {
            display: flex;

            div {
                display: flex;
                flex-direction: column;

                ul {
                    list-style-type: none;
                    margin-right: 25px;
                    margin-bottom: 15px;

                    h4 {
                        color: white;
                    }

                    li {
                        a {
                            color: gray;
                            text-decoration: none;
                        }
                    }
                }
            }


        }

        .img {
            width: 350px;
        }

    }


}
</style>
