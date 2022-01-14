<template>
  <div class="background">
    <div class="container">
      <div class="containerList">
        <div>
          <h3>DC COMICS</h3>
          <ul>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>
        </div>
        <div>
          <h3>DC</h3>
          <ul>
            <li>Terms Of Use</li>
            <li>Privacy policy (New)</li>
            <li>Ad Choices</li>
            <li>Advertising</li>
            <li>Jobs</li>
            <li>Subscription</li>
            <li>Talkent Workshops</li>
            <li>CPSC Certification</li>
            <li>Rating</li>
            <li>Shop Help</li>
            <li>Contact Us</li>
          </ul>
        </div>
        <div>
          <h3>SITES</h3>
          <ul>
            <li>DC</li>
            <li>MAD Magazine</li>
            <li>DC Kids</li>
            <li>DC Universe</li>
            <li>DC Power Visa</li>
          </ul>
        </div>
        <div>
          <h3>SHOP</h3>
          <ul>
            <li>Shop DC</li>
            <li>Shop DC Collectibles</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
name:'Footer',
data(){
  return{

  }
}
}
</script>

<style lang="scss" scoped>
.background{
  height: 400px;
  background-image: url(../assets/img/footer-bg.jpg);
  .container{
    padding: 2em 0;
    .containerList{
      width: 40%;
      display: flex;
      flex-wrap: wrap;
      div{
        padding-right: 2em;
        h3{
          padding-bottom: 0.5em;
          color: white;
        }
        ul{
          list-style: none;
          li{
            color: lightgray;
          }
        }
      }
    }
  }
}
</style>