<template>
  
<div class="am-background">

    <div class="container d-flex align-items-center">
        <div class="container row align-items-center">
            <div class="col">
                <button>SIGN-UP NOW!</button>
            </div>
        </div>   

        <div class="col d-flex">

            <div class="am-follow">
                FOLLOW US
            </div>

            <div class="am-social-icon">
                <img src="../assets/img/footer-facebook.png" alt="">
            </div>

            <div class="am-social-icon">
                <img src="../assets/img/footer-periscope.png" alt="">
            </div>

            <div class="am-social-icon">
                <img src="../assets/img/footer-pinterest.png" alt="">
            </div>

            <div class="am-social-icon">
                <img src="../assets/img/footer-twitter.png" alt="">
            </div>

            <div class="am-social-icon">
                <img src="../assets/img/footer-youtube.png" alt="">
            </div>
        </div>
                
    </div>
</div>

</template>




<!-- **********JAVASCRIPT*********** -->
<script>
export default {
name: 'SocialSection'
}
</script>




<!-- **********STYLE*********** -->
<style lang="scss" scoped>
  .am-background{
    background-color: #303030;
    height: 7rem;
  }

  .container{
    height: 100%;
  }

  button{
    padding: .7rem;
    color: white;
    background-color: #303030;
    border: solid 2px #0282F9;
  }

.am-follow{
    color: #0282F9;
    font-weight: 600;
    height: 100%;
    width: 6rem;
    }

.am-social-icon{
    margin: 0 0 0rem 2rem;
}

</style>