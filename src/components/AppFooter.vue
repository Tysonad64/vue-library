<script setup>
import { ref } from 'vue'
const footerMessage = ref('© 2025 Dark Matter Books')
</script>

<template>
    <footer>
        <span>{{ footerMessage }}</span>
    </footer>
</template>

<style scoped>
footer span{
    font-size: 1rem;
    text-align: center;
    margin: 1rem 0;
    padding: 0.5rem;
    display: block;
}
</style>