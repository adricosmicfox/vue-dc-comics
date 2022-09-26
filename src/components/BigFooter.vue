<template>
  
<div class="am-background d-flex justify-content-evenly">

  <div class="d-flex"> 
  <div class="am-list">
    <h4>DC COMICS</h4>
    <p>Characters</p>
    <p>Comics</p>
    <p>Movies</p>
    <p>TV</p>
    <p>Games</p>
    <p>Videos</p>
    <p>News</p>
  </div>

  <div class="am-list">
    <h4>SHOP</h4>
    <p>Shop DC</p>
    <p>Shop DC Collectibles</p>
  </div>

  <div class="am-list">
    <h4>DC</h4>
    <p>Term of use</p>
    <p>Privacy policy</p>
    <p>Ad Choices</p>
    <p>Advertising</p>
    <p>Jobs</p>
    <p>Subscriptions</p>
    <p>Talent Workshops</p>
    <p>CPSC Certificates</p>
    <p>Ratings</p>
    <p>Shop Help</p>
    <p>Contact Us</p>
  </div>

  <div class="am-list">
    <h4>SITES</h4>
    <p>DC</p>
    <p>MAD Magazine</p>
    <p>DC Kids</p>
    <p>DC Universe</p>
    <p>DC Power Visa</p>
  </div>
</div>

  <div>
    <img src="../assets/img/dc-logo-bg.png" alt="">
  </div>
</div>

</template>



<!-- **********JAVASCRIPT*********** -->
<script>
export default {
name: 'BigFooter'
}
</script>



<!-- **********STYLE*********** -->
<style lang="scss" scoped>
  .am-background{
    height: 30rem;
    background-image: url("../assets/img/footer-bg.jpg") ;
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
  }

.am-list p{
  color: rgb(154, 152, 152);
  line-height: .6rem;
}

.am-list h4{
  margin-bottom: 1.4rem;
  color: white;
}


</style>