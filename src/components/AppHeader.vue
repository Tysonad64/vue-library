<script setup>
import { ref } from 'vue'
const emoji = ref('🚀')
</script>

<template>
    <header>
        <span>Dark Matter Books{{ emoji }}</span>
    </header>
</template>

<style scoped>
header span{
    font-size: 2rem;
    text-align: center;
    margin: 1rem 0;
    padding: 0.5rem;
    display: block;
}
</style>