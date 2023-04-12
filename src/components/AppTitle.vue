<template>
    <header class="text-center">
    <h1>{{ titolo }}</h1>
    </header>
</template>

<script>
    export default {
        name:'AppTitle',
        data(){
            return{
                titolo:'La mia prima app con Vite!'
            }
        }
        
    }
</script>

<style lang="scss" scoped>

</style>