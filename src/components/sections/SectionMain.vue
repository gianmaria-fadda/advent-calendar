<script>

export default {
  data() {
    return { 
      items: []
    };
  },
  created() {
    // Ciclo per popolare l'array con 25 elementi
    for (let i = 1; i <= 25; i++) {
      this.items.push({
        id: i,
        text: i
      });
    }
  }
};
</script>

<template>
  <div class="container">
    <div class="row">
      <div class="col-1 mx-3 my-2 bg-success" v-for="item in items" :key="item.id">
        {{ item.text }}
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>

.container {

  width: 56%;
  
  .row {
    
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    flex-grow: 1;

    .col-1 {

      text-align: center;
      padding: 0 0;
      border-radius: 10px;
      color: white;
      font-weight: bold;
      font-size: 3rem;

    }
  }
}

</style>
