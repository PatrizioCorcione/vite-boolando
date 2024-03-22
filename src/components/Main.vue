<script>
import Card from '../components/Card.vue';
export default{
  components:{
    Card,
  }
}

</script>

<template>

  <div>
    <main class="main container">
      <Card/>
    
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