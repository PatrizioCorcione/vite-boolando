<script>
import Card from './Card.vue';
import {products} from '../assets/db.json/db.json';
export default{
  components:{
    Card,
  },
  data() {
    return {
      products
      
    }
  },
}

</script>

<template>

  <div>
    <main class="main container">
      <Card
        v-for="product in this.products"
        :key="product.id"
        :dress="product"
        
        
      />
    </main>
  </div>
  
</template>

<style lang="scss" scoped>

@import '../assets/scss/partials/utils';

.main{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  
}

</style>