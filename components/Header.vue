<script setup>
const runtimeConfig = useRuntimeConfig()
const appConfig = useAppConfig()
</script>
<template>
    <h1>{{runtimeConfig.title}}</h1>
    <h2>{{appConfig.title}}</h2>
</template>

<style lang="scss">
 
</style>