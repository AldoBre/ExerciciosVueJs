<template>
    <div>
        <button @click="primeiro($event), segundo($emit)">Ativar Multiplos Eventos</button>
        <p>{{ multiplos_eventos }}</p>
    </div>
</template>

<script>
export default{
    name: 'MultiplosEventos',
    data(){
        return{
            multiplos_eventos: ''
        }
    },
    methods:{
        primeiro(e){
            this.multiplos_eventos = 'Primeiro Evento Ativado'
        },
        segundo(e){
            setTimeout(() => this.multiplos_eventos = 'segundo evento!',500)
        }
    }
}

</script>

<style scoped>
    div{
        margin: 100px;
    }
</style>