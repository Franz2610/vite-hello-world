<template>
    <div class="jumbo text-center align-content-center bg-success text-white mt-5">
        <img :src="image" alt="vite">
       <h1>{{ icon }}</h1> 
        <img class="mb-2" :src="image2" alt="vite">
    </div>
    <div class="text-center">
        <h2>{{ jumbo }}</h2>
    </div>

</template>

<script>
    export default {
        name:'AppHero',
        data(){
            return{
                jumbo:'La fusione tra Vite e Vue',
                image :'https://vitejs.dev/logo-with-shadow.png',
                image2: 'https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1200px-Vue.js_Logo_2.svg.png',
                icon: '+'
            }
        }
        
    }
</script>

<style lang="scss" scoped>

</style>
