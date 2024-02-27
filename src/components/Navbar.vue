<script>
export default {
    name:"Navbar",
}  
</script>

<template>
  <div id=nav> 
    <router-link to="/" id=logourl>
         <img src="/img/logo.png" id="logo">
    </router-link>
    <router-link to="/"> Home </router-link>
    <router-link to="/Pedidos"> Pedidos </router-link>
  </div>
</template>

<style scoped>
    #nav{
        background-color: #222;
        border-bottom: 4px solid #111;
        padding: 15px 50px;
        display: flex;
        justify-content: flex-end;
        align-items: center;
    }
    #nav #logourl{
        margin: auto;
        margin-left: 0;
    }
    #logo{
        width: 40px;
        height: 40px;
    }

    #nav a{
        color :  #FCBA03;
        text-decoration: none;
        margin: 12px;
        transition: .5s; 
    }

    #nav a:hover {
        color: #FFF;
    }
   
</style>