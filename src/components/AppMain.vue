<script>
// 1) Importazione del componente
import SectionHeader from './sections/SectionHeader.vue';

export default {
  data() {
    return { 
      
    }
  },
  // 2) Dichiarazione del componente
  components: {
    SectionHeader
  }
}
</script>

<template>
  <main>
    <!-- 3) Utilizzo del componente -->
    <SectionHeader />
  </main>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

main {

  height: 100vh;
  background-color: #100645;
}

</style>
