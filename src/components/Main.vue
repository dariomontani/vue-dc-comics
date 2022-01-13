<template>
  <main>
    <h2 class="container">--&gt; Content goes here &lt;--</h2>
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
  height: 150px;
  display: flex;
  align-items: center;
  h2 {
    color: white;
  }
}
</style>