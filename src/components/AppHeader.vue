<script>

export default {
    name: "AppHeader",
    data() {
        return {

            links: [
                {
                    name: "CHARACTERS",
                    href: "#",
                    active: false
                },
                {
                    name: "COMICS",
                    href: "#",
                    active: true
                },
                {
                    name: "MOVIES",
                    href: "#",
                    active: false
                },
                {
                    name: "TV",
                    href: "#",
                    active: false
                },
                {
                    name: "GAMES",
                    href: "#",
                    active: false
                },
                {
                    name: "COLLECTIBLES",
                    href: "#",
                    active: false
                },
                {
                    name: "VIDEOS",
                    href: "#",
                    active: false
                },
                {
                    name: "FANS",
                    href: "#",
                    active: false
                },
                {
                    name: "NEWS",
                    href: "#",
                    active: false
                },
                {
                    name: "SHOP",
                    href: "#",
                    active: false
                },
            ]

        }
    }
}

</script>

<template>
    <header class="container">

        <div class="logo">
            <img src="../assets/images/dc-logo.png" alt="">

        </div>
        <div class="link">
            <ul>
                <li v-for="link in links">
                    <a :class="link.active == true ? 'active' : ''" href="link.href"> {{ link.name }}</a>
                </li>

            </ul>
        </div>





    </header>
</template>

<style lang="scss" scoped>
@use '../styles/partials/_mixins.scss' as *;

header {
    @include flex('space-between');
    align-items: center;
    padding: 40px 0;

    .logo {
        width: 50px;
    }

    .link {

        ul {
            @include flex('space-between');
            list-style-type: none;

            li {
                padding: 0 10px;

                a {
                    text-decoration: none;
                    color: black;

                    &.active {
                        color: #0282f9;
                    }
                }

            }
        }

    }
}
</style>
