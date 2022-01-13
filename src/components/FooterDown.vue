<template>
<div>
  <div class="container">
    <div class="button">
      <button>SIGN-UP NOW!</button>
    </div>
    <div class="follow">
      <h3>FOLLOW US</h3>
      <img src="..\assets\img\footer-facebook.png" alt="">
      <img src="..\assets\img\footer-twitter.png" alt="">
      <img src="..\assets\img\footer-youtube.png" alt="">
      <img src="..\assets\img\footer-pinterest.png" alt="">
      <img src="..\assets\img\footer-periscope.png" alt="">

    </div>
  </div>
</div>
</template>

<script>
export default {
    name: 'FooterDown',
    data(){
        return{
            
        }
    }
}
</script>

<style lang="scss" scoped>
div{
  background-color: #303030;
  height: 100px;
  display: flex;
  align-items: center;
  .container{
    display: flex;
    justify-content: space-between;
    align-items: center;
    .button button{
      color: white;
      padding: 1em;
      background-color: #303030;
      border: 1px solid #0c7cec;
    }
    .follow{
      display: flex;
      align-items: center;
      h3{
        color: #0c7cec;
      }
      img{
        padding-left: 1em;
      }
    }
  }
}
</style>