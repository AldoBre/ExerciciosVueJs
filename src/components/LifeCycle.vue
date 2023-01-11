<template>
    <h1>Meu Nome é: {{ nome }} </h1>
</template>

<script>

export default{
    name: 'LyfeCicle',
    data(){
        return{
            nome:'Ainda não sei'
        }
    },
    created(){
        setTimeout(() =>{
            this.nome = "Aldo Bressan"
        },1000)
        
    },
    mounted(){
        setTimeout(() =>{
            this.nome = "Aldo Programador"
        },2000)
        
    }
}
</script>