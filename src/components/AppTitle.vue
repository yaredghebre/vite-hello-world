<script>
export default {
    name: "AppTitle",
    data() {
        return {
            title: "La mia prima App con VITE!"
        }
    }
}
</script>

<template>
    <h1>{{ title }}</h1>
</template>

<style>
    h1 {
        text-align: center;
        margin: 50px;
    }
</style>