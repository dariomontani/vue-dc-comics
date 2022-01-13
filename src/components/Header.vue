<template>
  <div class="container">
      <img src="../assets/img/dc-logo.png" alt="">
      <ul>
          <li><a href="#">CHARACTERS</a></li>
          <li><a href="#">COMICS</a></li>
          <li><a href="#">MOVIES</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">GAMES</a></li>
          <li><a href="#">COLLECTIBLES</a></li>
          <li><a href="#">VIDEOS</a></li>
          <li><a href="#">FANS</a></li>
          <li><a href="#">NEWS</a></li>
          <li><a href="#">SHOP</a></li>
      </ul>
  </div>
</template>

<script>
export default {
    name: 'Header',
    data() {
        return {
        }
    }
}
</script>

<style lang="scss" scoped>
    img {
        display: block;
    }
    div {
        padding-top: 2em;
        display: flex;
        justify-content: space-between;
        align-items: center;
        ul{
            list-style: none;
            display: flex;
            align-items: center;
            li{
                padding-left: 2em;
                a{
                    text-decoration: none;
                    color: black;
                    &:hover,
                    &:active {
                        color: #0c7cec;
                        border-bottom: 2px solid #0c7cec;
                    }
                }
            }
        }
    }
</style>

