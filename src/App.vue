<template>
  <PrimeiroComponente/>
  <LyfeCicle/>
</template>

<script>
  import PrimeiroComponente from './components/PrimeiroComponente.vue'
  import LyfeCicle from './components/LifeCicle.vue'

  export default{
    name: 'App',
    components: {
      PrimeiroComponente,
      LyfeCicle
    }
  }

</script>