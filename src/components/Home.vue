<template>
  <div class="homePage">
    <div>
        <h1>Teste</h1>
      <div class="TituleNews">
        <h1>ÚLTIMAS NOTICIAS</h1>
        <H2></H2>
      </div>

      <div class="spaceNews">
        <div class="new">
          <div class="leftNews">
            <img class="img-50" src="../assets/tristana_image.png">
          </div>
          <div class="rightnews">

          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage'
}
</script>

<style scoped>
.homePage {
  width: 80%;
  display: flex;
  justify-content: center;
}
.spaceNews {
  display: flex;
}
  .img-50 {
    width: 100px;
    height: 100px;
  }
</style>
