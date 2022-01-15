<template>
    <div>
        <Header/>
        <h1>default layout</h1>
        <Nuxt/>
    </div>
</template>

<script>
import Header from '@/components/Header'

export default {
    components: {
        Header
    }
}
</script>

// Styles without scoped can be applied on all over the page
<style >
html , body {
    margin: 0;
}
</style>