<template>
    <nav class="container">
        <div class="row justify-content-between">
            <img class="navbar__logo" src="../assets/logo.svg" alt="">
            <div class="d-flex align-items-center">
                <a v-for="link in links" :key="link.href" :href="link.href"
                   class="px-3">
                    {{ link.title }}
                </a>
            </div>
        </div>
    </nav>
</template>

<script>
    export default {
        name: "Navbar",
        data: () => {
            return {
                links: [
                    {
                        title: "Проекты",
                        href: "#"
                    },
                    {
                        title: "Команда",
                        href: "#"
                    }
                ]
            }
        }
    }
</script>

<style scoped lang="scss">

    .navbar__logo {
        height: 170px;
        padding: 1rem 0;
    }

</style>