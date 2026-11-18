<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
    <nav class="nav">
        <ul>
            <li>
                <!-- <a href="http://"></a> -->
                 <router-link :to="{ name: 'guitarsList'}">Guitars</router-link>
            </li>

            <li>
                <!-- <a href="http://"></a> -->
                 <router-link :to="{ name: 'cart'}">Cart</router-link>
            </li>
        </ul>
    </nav>
</template>

<style scoped>
.nav {
    background: var(--dark);
}
</style>