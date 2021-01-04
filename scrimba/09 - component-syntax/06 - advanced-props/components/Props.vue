<template>
    <div>
        <h1>Advanced Props</h1>
        
        <div>{{ isPublished }}</div>
    </div>
</template>

<script>
    module.exports = {
        props: {
            // ini tuh pengganti type, jadi sama aja kaya id: {type: Number}
            id: Number,
            title: String,
            isPublished: {
                // ini bisa acc 2 jenis tipe data
                type: [Boolean, Number],
                // kalau misalnya nanti props isPublished tidak didefenisikan, maka isPublished bernilai false (kalau dibuat atribut default)
                default: false
            },
            views: Number,
        }
    }
</script>

<style>
    
</style>