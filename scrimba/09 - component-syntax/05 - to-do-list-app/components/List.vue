<template>
    <ul>
        <li v-for="item in items" :key="item">{{ item }}</li>
    </ul>
</template>

<script>
    module.exports = {
        props: ['items']
    }
</script>

<style></style>