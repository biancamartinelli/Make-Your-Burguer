<template>
    <footer id="footer">
        <p>Make Your Burguer &copy; 2023</p>
    </footer>
</template>

<script>
    export default {
        name: "Footer"
    }
</script>

<style>
    #footer {
       height: 100px;
       background-color: #222; 
       border-top: 4px solid #111;
       color: #FCBA03;
       display: flex;
       align-items: center;
       justify-content: center;
       bottom: 5;
       width: 100%;
       position: absolute;
    }
</style>