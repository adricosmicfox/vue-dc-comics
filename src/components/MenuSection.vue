<template>
  
  <div class="am-background">
    <div class="container">
        <div class="row d-flex align-items-center am-icons-container">
            <div class="col">
                <img class="img-fluid" src="../assets/img/buy-comics-digital-comics.png" alt="">
                 <span>DIGITAL COMICS</span>
            </div>

            <div class="col">
                <img  class="img-fluid" src="../assets/img/buy-comics-merchandise.png" alt="">
                <span>DC MERCHANDISE</span>
            </div>

            <div class="col">
                <img  class="img-fluid" src="../assets/img/buy-comics-subscriptions.png" alt="">
                <span>SUBSCRIPTION</span>
            </div>

            <div class="col">
                <img  class="img-fluid" src="../assets/img/buy-comics-shop-locator.png" alt="">
                <span>COMIC SHOP LOCATOR</span>
            </div>

            <div class="col">
                <img  class="img-fluid" src="../assets/img/buy-dc-power-visa.svg" alt="">
                <span>DC POWER VISA</span>
            </div>
        </div>
    </div>
  </div>


</template>




<!-- **********JAVASCRIPT*********** -->
<script>
export default {
name: 'MenuSection'
}
</script>




<!-- **********STYLE*********** -->
<style lang="scss" scoped>
  .am-background{
    background-color: #0282F9;
    height: 13rem;
  }

  img{
    width: 3rem;
  }

  span{
    color: white;
    margin-left: .5rem;
  }

.am-icons-container{
    height: 13rem;
}

</style>



