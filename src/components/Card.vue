<script>

</script>

<template>
    <div>
        <img :src="url" alt="nombre">
        <h2>{{producto}}</h2>
        <p>Descripción: {{nombre1}}</p>
        <p>$ {{costo}}.00</p>
    </div>
</template>

<style scoped>
    div{
        display: inline-block;  
        text-align: center;
        border: 1px solid ;
        border-radius: 5px;
        margin: 4px; 
        width: 23%;
        height: 45vh;
    }
    img{
        width: 9rem;
        height: 9rem;
        padding: 0.5rem;
        border-radius: 10px;
    }
    h2{
        color:violet;
        font-size: 25px;
    }
    h2,p{
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }
</style>

<script>
    export default{
        props: {
            url:{
                String,
            },
            nombre: {
                String,
            },
            nombre1:{
                String,
            },
            producto:{
                String,
            },
           costo:{
            Number,
           },
        },
    };
</script>