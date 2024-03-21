<script>

</script>

<template>

  <div>
    <div class="footer-back">
    <div class="container flex-footer">
      <div class="legal">
        <strong class="white">Boolando s.r.l.</strong>
        <ul class="footer-ul">
          <li><a href="">Informazioni legali</a></li>
          <li><a href="">Informative sulla privacy</a></li>
          <li><a href="">Diritto di recesso</a></li>
        </ul>
      </div>
      <div class="find">
        <p class="white">Trovaci anche su:</p>
        <ul class="flex-icon">
          <li><a href=""><i class="fa-brands fa-square-twitter"></i></a></li>
          <li><a href=""><i class="fa-brands fa-square-facebook"></i></a></li>
          <li><a href=""><i class="fa-brands fa-square-instagram"></i></a></li>
          <li><a href=""><i class="fa-brands fa-square-pinterest"></i></a></li>
          <li><a href=""><i class="fa-brands fa-square-youtube"></i></a></li>
        </ul>
      </div>
    </div>
  </div>
  </div>
  
</template>

<style lang="scss" scoped>

@import '../assets/scss/partials/variables';
@import '../assets/scss/partials/general';

.footer-back{
  background-color: $footerBack;
  .flex-footer{
    height: 100px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    .legal{
      width: 85%;
      strong{
        color: $primary;
      }
      .footer-ul{
        margin-top: 5px;
        width: 53%;
        display: flex;
        justify-content: space-between;
      }
    }
    .find{
      width: 15%;
      .flex-icon{
        margin-top: 5px;
        width: 65%;
        display: flex;
        justify-content: space-between;
      }
      p{
        color: $primary;
      }

    }
    
  }
}

</style>
