<script setup>
import {ref} from 'vue'

const welcomeMessage = ref('Welcome to DMB HQ! Your portal to the ever expanding universe of books!')
</script>

<template>
    <main>
        <h2>{{ welcomeMessage }}</h2>
    </main>
</template>

<style scoped>
main h2{
    font-size: 1.5rem;
    text-align: center;
    margin: 1rem 0;
}
</style>