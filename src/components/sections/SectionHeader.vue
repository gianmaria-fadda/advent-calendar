<script>

export default {
  data() {
    return { 
      
    }
  }
}
</script>

<template>
  <div class="container rounded-5 rounded-top-0">
    <div class="row">
      <div class="col">
        <h3>
          Advent Calendar<br>2024 
        </h3>
        <div class="img-container rounded-5 rounded-top-0">

        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>

.container {

  background-color: #2D28EB;
  height: 300px;
  width: 56%;
  position: relative;

  
  .row {
    

    .col {

      

      h3 {

        color: white;
        text-align: center;
        margin-top: 40px;
      }

      .img-container {

        background-image: url(/public/images/header-bg.png);
        background-repeat: no-repeat;
        object-fit: cover;
        height: 230px;
        width: 100%;
        position: absolute;
        left: 0;
        bottom: 0;
      }
    }
  }
}

</style>
