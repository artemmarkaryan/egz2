<template>
    <div id="homepage">

        <navbar></navbar>

        <h1 class="col-3" v-html>— оформляем и&nbsp;продвигаем бизнес в&nbsp;интернете</h1>


    </div>
</template>

<script>
    import Navbar from "./Navbar";
    export default {
        name: "Homepage",
        components: {
            Navbar
        }
    }
</script>

<style scoped>

</style>