<script>



</script>

<template>

  <div class="header">
    <div class="container flex-top">
      <nav class="nav-text">
        <ul class="flex-ul-txt">
          <li><a class="white" href="">Donna</a></li>
          <li><a class="white" href="">Uomo</a></li>
          <li><a class="white" href="">Bambini</a></li>
        </ul>
      </nav>
      <div class="logo">
        <img src="../assets/img/boolean-logo.png" alt="Boolando">
      </div>
      <nav class="nav-icon">
        <ul class="flex-ul">
          <li><a href=""> <i class="fa-regular fa-user"></i> </a></li>
          <li><a href=""><i class="fa-regular fa-heart"></i></a></li>
          <li><a href=""><i class="fa-solid fa-bag-shopping"></i></a></li>
          
        </ul>
      </nav>
    </div>
  
  </div>
  
</template>



<style lang="scss" scoped>

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
      display: flex;
      align-items: center;
      justify-content: center;
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