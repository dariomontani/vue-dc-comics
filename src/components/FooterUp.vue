<template>
  <div>
    <ul class="container">
      <li>
        <img src="..\assets\img\buy-comics-digital-comics.png" alt="">
        <h5>DIGITAL COMICS</h5>
      </li>
      <li>
        <img src="..\assets\img\buy-comics-merchandise.png" alt="">
        <h5>DC MERCHANDISE</h5>
      </li>
      <li>
        <img src="..\assets\img\buy-comics-subscriptions.png" alt="">
        <h5>SUBSCRIPTION</h5>
      </li>
      <li>
        <img src="..\assets\img\buy-comics-shop-locator.png" alt="">
        <h5>COMIC SHOP LOCATOR</h5>
      </li>
      <li>
        <img src="..\assets\img\buy-dc-power-visa.svg" alt="">
        <h5>DC POWER VISA</h5>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
    name: 'FooterUp',
    data(){
        return{

        }
    }
}
</script>

<style lang="scss" scoped>
div {
  background-color: #0c7cec;
  height: 150px;

  ul {
    list-style: none;
    height: 100%;
    display: flex;
    align-items: center;
    li{
      display: flex;
      align-items: center;
      img{
        width: 2em;
        margin-left: 3em;
      }
      h5{
        color: white;
        padding-left: 1em;
      }
    }
  }

}
</style>