<script>
export default {
  data(){
    return{
      size:[
        {
          target:'Uomo',
          lick:'#',
        },
        {
          target:'Donna',
          lick:'#',
        },
        {
          target:'Bambino',
          lick:'#',
        },
      ],
      icons:[
        {
          icon:'fa-regular fa-user',
          lick:'#',
        },
        {
          icon:'fa-regular fa-heart',
          lick:'#',
        },
        {
          icon:'fa-solid fa-bag-shopping',
          lick:'#',
        }
      ]

    }
  }
}


</script>

<template>

  <div class="header">
    <div class="container flex-top">
      <nav class="nav-text">
        <ul class="flex-ul-txt">
          <li
          v-for="(element,index) in size " :key="index"
          ><a class="white" :href="element.link">{{ element.target }}</a></li>
         
        </ul>
      </nav>
      <div class="logo">
        <img src="../assets/img/boolean-logo.png" alt="Boolando">
      </div>
      <nav class="nav-icon">
        <ul class="flex-ul">
          <li
          v-for="(element,index) in icons" :key="index"
          ><a :href="element.link"> <i :class="element.icon"></i> </a></li>
          
          
        </ul>
      </nav>
    </div>
  
  </div>
  
</template>



<style lang="scss" scoped>

@use '../assets/scss/partials/mixin' as *;

@import '../assets/scss/partials/general';
@import '../assets/scss/partials/variables'; 

.header{
  height: 60px;
  top: 0;
  z-index: 999;
  position: fixed;
  width: 100%;
  background-color: $headerBack;
  .container{
    margin-bottom: 50px;
    height: 60px;
    display: flex;
    justify-content: space-around;
    align-items: center;
    .nav-text{
      width: 40%;
      .flex-ul-txt{
        width: 40%;
        display: flex;
        justify-content: space-between;
      }
    }
    .logo{
      @include centerFlex();
      img{
      width: 20%;
    }
    
    }
    .nav-icon{
      display: flex;
      justify-content: flex-end;
      width: 40%;
      .flex-ul{
        width: 20%;
        display: flex;
        justify-content: space-between;
      }
    }
  }

}

</style>