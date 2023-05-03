<script>
export default{
        name: "AppFooter_e",
    }
</script>

<template>
  <div id="container">
    <button type="button" class="btn btn-outline-primary">SIGN-UP NOW!</button>
    <div class="box">
      <span>FOLLOW US</span>
      <img src="/img/footer-facebook.png" alt="">
      <img src="/img/footer-twitter.png" alt="">
      <img src="/img/footer-youtube.png" alt="">
      <img src="/img/footer-pinterest.png" alt="">
      <img src="/img/footer-periscope.png" alt="">
    </div>
  </div>
</template>

<style lang="scss" scoped>
    #container{
        width: 100%;
        height: 150px;
        background-color: rgb(34, 34, 34);
        position: relative;
        z-index: 9;
        display: flex;
        justify-content: space-around;
        align-items: center;
        .box{
            display: flex;
            justify-content: space-between;
            width: 20%;
        }
        button{
            color: white;
        }
        span{
            color: blue;
            font-size: 26px;
        }
    }

</style>