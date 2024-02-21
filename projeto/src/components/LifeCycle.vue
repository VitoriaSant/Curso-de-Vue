<template>
<h1> Meu nome é {{ name }}</h1>
</template>

<script>

export default {
    name: 'LifeCycle',
    data() {
        return {
            name: ' ainda nao sei'
        }
    },
    created () {
        this.name = 'Vitoria'
    },
    mounted() {
        this.name = 'thiago'
    }
}
</script>
