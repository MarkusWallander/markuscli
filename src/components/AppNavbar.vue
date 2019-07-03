<template>
    <nav class="h-16 fixed w-full flex justify-between items-center px-8" >
       <h1 class="logo">Walle</h1>
       <ul>
        <li class="active">Home</li> 
        <li>About</li>
        <li>Contact</li>
        </ul>


    </nav>
</template>
<script>
export default {
    name: 'AppNavbar'
}
</script>
<style scoped>
    .logo {
        font-size: 2.5rem;
        color: white;
    }

    ul {
        display: flex; 
        
    }

    li{ 
        font-size: 1.2rem;
        margin-left: 1rem;
        color: white;
    }

    .active{
       border-bottom: 2px solid black; 
    }

  

</style>