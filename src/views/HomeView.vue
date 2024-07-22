<!-- TEMPLATES -->
<template>
    <div class="home">
        <h1 class="text-center text-principal protest-revolution-regular my-5"> Vista Principal</h1>
    </div>
</template>

<!-- SCRIPTS -->
<script>
export default {
    data() {
        return {
            dstosGlobales: this.datosContacto,
        };
    },
    components: {},
    created() {
        console.log(this.datosGlobales);
    },
    name: "HomeView",
    components: {},
};
</script>

<!-- STYLES -->
<style scoped>
.home {
    min-height: 100vh;
}
</style>