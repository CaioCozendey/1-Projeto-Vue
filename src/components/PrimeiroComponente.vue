<template>
    <div>
        <h1> Olá Mundo! </h1>
        <p> Meu nome é: {{ nome }} <br> e sou um {{ profissao }}</p>
    </div>
</template>

<script>
export default {
    name: 'PrimeiroComponente',
    data() {
        return {
            nome: "Caio",
            profissao: "Dev"
        }
    }
}
</script>