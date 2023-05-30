<template>
    <div class="contact">
        <Title :title="contactTitle"/>
    </div>
</template>

<script setup>
import Title from '../components/Title.vue'

const contactTitle = "Hello from contact view"
</script>