<script>
export default{
  data(){
    props:{
      

    }
  }
}

</script>
<template>
  
    <div class="cards">
      <div class="card">
        <img src="/src/assets/img/1.webp" alt="">
        <img class="cardb" src="/src/assets/img/1b.webp" alt="">
        <i id="heart" class="fa-solid fa-heart"></i>
      
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

@import '../assets/scss/partials/_variables.scss';

.cards{
  margin-top: 120px;
  margin-bottom: 35px;
  width: 32%;
  .card{
    &:hover .cardb{
      display: block;
    }
    position: relative;
    .cardb{
      display: none;
      position: absolute;
      top: 0;
    }
    #heart{
      padding: 20px;
      background-color: $primary;
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
       color: $primary;
       padding: 1px 4px;
       background-color: $priceDiscount;
      }
      .quality{
        font-size: 0.9rem;
        width: 8%;
        color: $primary;
        padding: 1px 4px;
        background-color: $type;
      }
    }
  }
  .red{
    color: $priceDiscount;
  }
  .gray-line{
    margin-left: 5px;
    text-decoration: line-through;
    color: $priceOverline;
  }
}

</style>