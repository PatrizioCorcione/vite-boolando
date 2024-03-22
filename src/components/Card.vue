

<script>
</script>
<template>
  
    <div class="cards">
      <div class="card">
        <img src="/src/assets/img/1.webp" alt="">
        <img class="cardb" src="/src/assets/img/1b.webp" alt="">
        <i id="heart" class="fa-sharp fa-regular fa-heart"></i>
      
        <div class="labels">
          <span class="discount">-50%</span>
          <span class="quality">Sostenibilita</span>
        </div>
      </div>
      <div class="text">
        <p>Levi's</p>
        <strong>RELAXED FIT TEE UNISEX</strong>
        <div class="marc">
          <span class="red">14.99 &#8364;</span><span class="margin-price gray-line">29.99 &#8364;</span>
        </div>
      </div>
    </div>  
  
</template>
<style lang="scss">
.cards{
  margin-top: 120px;
  margin-bottom: 35px;
  width: 32%;
  .card{
    position: relative;
    .cardb{
      display: none;
      position: absolute;
      top: 0;
    }
    #heart{
      padding: 20px;
      background-color: rgb(255, 255, 255);
      right: 0;
      top: 20px;
      position: absolute;
    }
    .labels{
      position: absolute;
      left: 0;
      bottom: 20px;
      .discount{
        font-size: 0.9rem;
       width: 4%;
       color: white;
       padding: 1px 4px;
       background-color: red;
      }
      .quality{
        font-size: 0.9rem;
        width: 8%;
        color: white;
        padding: 1px 4px;
        background-color: rgb(0, 220, 77);
      }
    }
  }
  .red{
    color: red;
  }
  .gray-line{
    margin-left: 5px;
    text-decoration: line-through;
    color: gray;
  }
}

</style>