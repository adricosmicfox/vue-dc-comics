<template>
  
    <div class="container progress bg-white" style="height:10rem">
        <div class="container row align-items-center progress bg-white" style="height:10rem">
            <div class="col">
            <img src="../assets/img/dc-logo.png" alt="">
            </div>
            
            <div class="col">
                <ul class="d-flex ">
                    <li>CHARACTERS</li>
                    <li>COMICS</li>
                    <li>MOVIES</li>
                    <li>TV</li>
                    <li>GAMES</li>
                    <li>COLLECTIBLES</li>
                    <li>VIDEOS</li>
                    <li>FANS</li>
                    <li>NEWS</li>
                    <li>SHOP</li>
                </ul>
            </div>
        </div>
    </div>



</template>



<!-- **********JAVASCRIPT*********** -->
<script>
export default {
name: 'HeaderComponent'
}
</script>



<!-- **********STYLE*********** -->
<style lang="scss" scoped>
 ul{
    list-style: none;
 }

 li{
    font-size: small;
    margin-right: 2rem;
 }


</style>