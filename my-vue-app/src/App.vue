<template>
  <div>
    <span @click="cambiaNome" class="nome">{{ nome }}</span>
  </div>
</template>

<script>
export default {
  data() {
    return {
      nome: 'Giada',
    }
  },
  methods: {
    cambiaNome() {
      this.nome = "Volpin";
    }
  }
}
</script>

<style lang="css" scoped>
.nome {
  color: green;
}
</style>