<template>
    <div>
        
        <h1>Olá Vue</h1>
        <p>{{ nome }}</p>

        <MultiplosEventos/>
        <Reutilizacao/>
        <Reutilizacao/>
        <Reutilizacao/>
        <Reutilizacao/>
        <Reutilizacao/>
    </div>
</template>

<script>
    import MultiplosEventos from './MultiplosEventos.vue'
    import Reutilizacao from './Reutilizacao.vue';

    export default{
        name:'primeiroComponente',
        components:{
            MultiplosEventos,
            Reutilizacao
        },
        data(){
            return{
                nome: 'Aldo'
            }
        }
    }
</script>