<template>
    <h3> Meu nome é: {{ nome }}</h3>
</template>

<script>
export default {
    name: 'LyfeCicle',
    data() {
        return {
            nome: "Só Deus sabe"
        }
    },
    created() {
        setTimeout(() => {
            this.nome =  "Caio"    
        }, 1000);  
    },
    mounted() {
        setTimeout(() => {
            this.nome = "Pedro"
        }, 2000);
    }
}
</script>