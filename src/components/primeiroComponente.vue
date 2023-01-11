<template>
    <div>
        
        <h1>Olá Vue</h1>
        <p>{{ nome }}</p>
    </div>
</template>

<script>


    export default{
        name:'primeiroComponente',
        data(){
            return{
                nome: 'Aldo'
            }
        }
    }
</script>