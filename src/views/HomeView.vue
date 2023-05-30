<template>
  <div class="home">
    <Title :title="homeTitle"/>
  </div>
</template>

<script setup>
import Title from '../components/Title.vue'

const homeTitle = "Hello from home view"
</script>