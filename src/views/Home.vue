<template>
    <Banner />
    

    <BurgerForm />
</template>

<script>
import BurgerForm from '@/components/BurgerForm.vue'
import Banner from "../components/Banner.vue"


export default{
    name: "Home",
    components: {
        Banner,
        BurgerForm
    }
}

</script>

<style>

</style>
