<template>
  <main class="wrapper">
    <section class="featured-box">
      <div>
        <section class="lastnewsTitule">
          <h1 class="titleLast">ÚLTIMAS NOTICIAS</h1>
          <H2 class="lineMain"></H2>
        </section>

        <div class="spaceNews">
          <div class="new">
            <div class="leftNews">
              <img class="img-50" src="../assets/tristana_image.png">
            </div>
            <div class="rightnews">
              <img class="img-25 img25-1" src="../assets/valorant_image.png">
              <img class="img-25" src="../assets/valorant_image.png">
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
export default {
  name: 'HomePage'
}
</script>

<style scoped>
@import url('https://fonts.cdnfonts.com/css/gilroy-bold');

html,
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.wrapper {
  width: 100%; /* Tornar o wrapper 100% da largura do elemento pai */
  display: flex;
  justify-content: center;
  align-items: center;
}

.featured-box {
  /* Adiciona margem superior e inferior para espaçamento */
  margin-top: 20px;
  margin-bottom: 20px;
  width: 80%;
}

.lastnewsTitule {
  display: flex;
  flex-direction: column;
}

.titleLast {
  display: flex;
  justify-content: left;
  font-size: 30px;
  font-family: 'Gilroy-Regular', sans-serif;
  margin-bottom: 0px;
}

.lineMain {
  border-bottom: 1px solid #ccc; /* Adiciona uma borda inferior cinza */
  margin-bottom: 20px; /* Adiciona espaço abaixo da linha */
}

.spaceNews {

}

.new {
  display: flex;
  justify-content: center;
}

.leftNews {

}

.rightnews {
  display: flex;
  flex-direction: column;
}

.img-50 {
  justify-content: left;
  height: 400px;
  margin-left: 0
}

.img-25 {
  height: 190px;
  margin-left: 20px;
}

.img25-1 {
  margin-bottom: 18px;
}
</style>
