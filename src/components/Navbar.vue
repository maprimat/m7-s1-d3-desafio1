<!-- TEMPLATES -->
<template lang="">
    <nav class="navbar navbar-expand-lg navbar-light sticky-top protest-revolution-regular">
        <div class="container px-4">

            <a class="navbar-brand" href="#">
                <img src="../assets/img/logo.png" alt="logo de suricata" />
            </a>

            <button class="navbar-toggler navbar-dark border-light" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ms-auto">
                <!-- Reemplazamos los 'a' por 'router-link' y los 'href=' por 'to=' -->
                <!-- En la etiqueta "to" agregamos los path -->
                <li class="nav-item active">
                    <router-link class="nav-link text-light mx-2" to="/">Inicio</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link text-light mx-2" to="/productos">Productos</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link text-light mx-2" to="/contacto">Contacto</router-link>
                </li>
                </ul>
            </div>
            
        </div>
    </nav>
</template>

<!-- SCRIPTS -->
<script>
export default {
    name: "Navbar",
    props: {},
};
</script>

<!-- STYLES -->
<style scoped lang="scss"></style>