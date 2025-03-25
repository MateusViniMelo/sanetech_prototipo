<template>
    <div class="bg-white">
        <div class="container">
            <footer class="py-3 mt-4">
                <ul class="nav justify-content-center border-bottom pb-3 mb-3">
                    <li class="nav-item">

                        <RouterLink to="/" class="nav-link px-2 text-body-secondary">Início</RouterLink>
                    </li>
                    <li class="nav-item">
                        <RouterLink to="/produtos" class="nav-link px-2 text-body-secondary">Produtos</RouterLink>
                    </li>
                    <li class="nav-item">
                        <RouterLink to="/servicos" class="nav-link px-2 text-body-secondary">Serviços</RouterLink>
                    </li>
                    <li class="nav-item">
                        <p href="#" class="nav-link px-2 text-body-secondary">FAQs</p>
                    </li>
                    <li class="nav-item">
                        <p href="#" class="nav-link px-2 text-body-secondary">Sobre</p>
                    </li>
                </ul>
                <p class="text-center text-body-secondary">© 2024 SaneTech</p>
            </footer>
        </div>
    </div>
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<style scoped></style>