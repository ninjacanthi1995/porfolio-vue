<template>
  <div class="header">

    <div></div>

    <div class="middle-div">

      <img src="./laptop.svg" alt="">

      <h1>{{ name }}</h1>

      <p>{{ profession }}</p>

    </div>

    <div></div>

  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    name: String,
    profession: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

  .header {
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    background-color: #e9d5a1;

    .middle-div {
      display: flex;
      flex-direction: column;
      align-items: center;

      img {
        width: 150px;
        height: 150px;
      }

      h1 {
        font-size: 40px;
        margin: 10px 0px;
      }

      p {
        font-size: 30px;
        font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        margin: 10px 0px;
      }

    }

  }

</style>
