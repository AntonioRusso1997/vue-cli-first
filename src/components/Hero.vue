<template>
<div>
    <h2>Quando scopri che non era stata avviata la registrazione:</h2>
    <img src="../assets/img1.gif" alt="">
</div>
</template>

<script>
export default {
  name: 'Hero',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
img {
    height: 700px;
    border: 10px solid lightblue;
    border-radius: 30px;
}

h2 {
    color: black;
    font-size: 28px;
}
</style>
