<template>
    <div>
    <h1>Olá vie </h1>
    <p>Me nome é {{ name }}</p>
    </div>
</template>


<script> 
export default ({
    name: 'PrimeiroComponente',

    data(){
        return{
            name:"vitoria",
        }
    }
})
</script>
