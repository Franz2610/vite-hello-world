<template>
    <div class="jumbo text-center align-content-center">
   <h3>{{ jumbo }}</h3> 
   <img :src="image" alt="vite">
    
    </div>
</template>

<script>
    export default {
        name:'AppHero',
        data(){
            return{
                jumbo:'Jumbo!',
                image :'https://vitejs.dev/logo-with-shadow.png'
            }
        }
        
    }
</script>

<style lang="scss" scoped>

</style>
