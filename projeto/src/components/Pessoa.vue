<template>
    <h2>Esta é a descrição de pessoa: {{ name }}</h2>
</template>


<script>
export default {
    name: 'pessoa',
    data() {
        return{
            name: 'vitoria'
        }
    }
 }
</script>