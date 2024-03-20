<script>
export default {
  data(){
    return {
      title: 'Il mio primo progetto con VITE!',
      description:'Questo è il mio primo progetto creato da linea di comando grazie a VITE.'
    }
  }
}
</script>

<template>
  <div>
    <h1>{{ title }}</h1>
    <p>{{ description }}</p>
  </div>
</template>

<style scoped>
  h1{
    color:red;
  }
</style>