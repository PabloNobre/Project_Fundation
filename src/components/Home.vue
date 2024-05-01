<template>
  <main class="wrapper">
    <section class="featured-box">
      <div>
        <section class="lastnewsTitule">
          <h1 class="titleLast">ÚLTIMAS NOTICIAS</h1>
          <H2 class="lineMain" id="line01"></H2>
        </section>

        <div>
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
      <section class="lastnewsTitule2">
        <H2 class="lineMain"></H2>
        <h1 class="titleLast">CRONOGRAMA</h1>
      </section>
      <div class="cronograma-new">
        <div class="newCronograma">
          <div class="leftCro">
            <h1 class="subTitleLast"> TERÇA 23/04</h1>
            <div>
              <img class="ImageNew" src="../assets/cs2_image.png">
            </div>
          </div>
          <div class="textnew">
            <h1 class="namePost">COUNTER STRIKER 2</h1>
            <h1 class="subPost">ERROR 404</h1>
            <p class="subtitle">Erros da Valve com CS2 já têm consequências e algo precisa ser feito.</p>
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
  margin-top: 20px;
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
  margin-bottom: 0px; /* Adiciona espaço abaixo da linha */
}

#line01 {
  margin-bottom: 20px;
}

.new {
  display: flex;
  justify-content: center;
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

.lastnewsTitule2 {
  display: flex;
  justify-content: left;
}
.cronograma-new .new {
  justify-content: flex-start; /* Alinha o .new à esquerda */
}

.newCronograma {
  display: flex;
}

.leftCro {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

.subTitleLast {
  font-size: 18px;
  font-family: 'Gilroy-Bold', sans-serif;
}

.ImageNew {
    height: 220px;
    width: 400px;
}

.textnew {
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  align-items: flex-start;
}

.namePost {
  margin: 0;
}

.subPost {
  margin: 0;
}

.subtitle {
  margin-bottom: 0;
  margin-top: 2px;
}
</style>
