<template>
    <div class="bg-white border-bottom mb-4">
        <div class="container">
            <header class="d-flex flex-wrap justify-content-center py-4 ">
                <RouterLink to="/"
                    class="d-flex align-items-center mb-3 mb-md-0 me-md-auto link-body-emphasis text-decoration-none me-2">
                    <i class="bi bi-droplet-fill me-2 fs-3 text-primary"></i>
                    <span class="fs-4">SaneTech</span>
                </RouterLink>


                <ul class="nav nav-pills">

                    <li class="nav-item">
                        <RouterLink to="/" class="nav-link" active-class="active">Início</RouterLink>

                    </li>
                    <li class="nav-item">

                        <RouterLink to="/produtos" class="nav-link" active-class="active">Produtos</RouterLink>
                    </li>
                    <li class="nav-item">
                        <RouterLink to="/servicos" class="nav-link" active-class="active">Serviços</RouterLink>
                    </li>

                </ul>
            </header>
        </div>
    </div>
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>
<style scoped>
.azul {
    color: rgb(0, 162, 255);
}
</style>
