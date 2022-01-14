<template>
  <main>
    <div class="containerCards">
      <div class="card">
        <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
        <h3>ACTION COMICS</h3>
      </div>
    </div>
  </main>
</template>

<script>
export default {
    name: 'Main',
    data(){
        return {

        }
    }
}
</script>

<style lang="scss" scoped>
main {
  background-color: black;
  display: flex;
  align-items: center;
  .containerCards{
    .card{
      h3{
        color: white;
      }
    }
  }
}
</style>