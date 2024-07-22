<!-- TEMPLATES -->
<template>
    <div class="contacto text-center protest-revolution-regular text-principal">
        <h1 class="text-center text-principal protest-revolution-regular my-5">
            Contactos
        </h1>
        <div class="text-center py-5">
            <router-link class="btn my-5" to="/">Volver al Inicio</router-link>
        </div>
    </div>
</template>

<!-- SCRIPTS -->
<script>
export default {
    name: "ContactoView",
};
</script>

<!-- STYLES -->
<style scoped>
.btn{
    background-color: #E83E8C;
    color: white;
}
.contacto {
    min-height: 100vh;
}
</style>
