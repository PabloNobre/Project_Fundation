<template>
  <main class="wrapper">
    <section class="featured-box">

      <div class="lastNews">
        <section class="lastnewsTitule">
          <h1 class="titleLast">ÚLTIMAS NOTICIAS</h1>
          <H2 class="lineMain" id="line01"></H2>
        </section>

        <div>
          <div class="new">
            <div class="leftNews">
              <div class="image-container">
                <img class="img-50" src="../assets/tristana_image.png">
                <div class="image-info">
                  <p class="namePost">LEAGUE OF LEGENDS</p>
                  <p class="subPost">LEAGUE DISPLAY</p>
                  <p class="subtitle">Protetores de tela e fundos de tela em HD, diretamente para sua área de trabalho</p>
                </div>
              </div>
            </div>
            <div class="rightnews">
              <div class="image-container">
                <img class="img-25" src="../assets/valorant_image.png">
                <div class="image-info-25">
                  <p class="namePost">VALORANT</p>
                  <p class="subPost">VALORANT MOBILE</p>
                  <p class="subtitle">Valorant é o próximo sucesso dos games</p>
                  <p class="subtitle-2">e ganha versão mobile</p>
                </div>
              </div>
              <div class="image-container">
                <img class="img-25" src="../assets/free_fire_image.png">
                <div class="image-info-25">
                  <p class="namePost">FREE FIRE</p>
                  <p class="subPost">FREE FIRE RECEBE QUEBRANDO GELO</p>
                  <p class="subtitle">A Garena anunciou, na última quarta-feira,</p>
                  <p class="subtitle-2">que o festival de Ano Novo está de volta.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <section class="lastnewsTitule2">
        <H2 class="lineMain"></H2>
        <h1 class="titleLast" id="cronogramaPage">CRONOGRAMA</h1>
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
        <H2 class="linemain2"></H2>
      </div>

      <div class="cronograma-new">
        <div class="newCronograma">
          <div class="leftCro">
            <h1 class="subTitleLast"> SEGUNDA 22/04</h1>
            <div>
              <img class="ImageNew" src="../assets/fortnite_image.png">
            </div>
          </div>
          <div class="textnew">
            <h1 class="namePost">FORTNITE</h1>
            <h1 class="subPost">CAMPEONATO GLOBAL DO FNCS 2024</h1>
            <p class="subtitle">Podem anotar na agenda os dias 7 e 8 de setembro. A ação frenética do FNCS 2024 terá seu desfecho na Dickies Arena, em Fort</p>
            <p class="subtitle">Worth, Texas (EUA)!</p>
          </div>
        </div>
        <H2 class="linemain2"></H2>
      </div>

      <div class="cronograma-new">
        <div class="newCronograma">
          <div class="leftCro">
            <h1 class="subTitleLast"> DOMINGO 21/04</h1>
            <div>
              <img class="ImageNew" src="../assets/free_fire_image.png">
            </div>
          </div>
          <div class="textnew">
            <h1 class="namePost">FREE FIRE</h1>
            <h1 class="subPost">FREE FIRE RECEBE QUEBRANDO GELO</h1>
            <p class="subtitle">A Garena anunciou, na última quarta-feira (20), que o festival de Ano Novo está de volta em Free Fire. Quebrando o Gelo traz </p>
            <p class="subtitle">diversas novidades...</p>
          </div>
        </div>
        <H2 class="linemain2"></H2>
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
  background-image: url('../assets/bg_branco.png');
  background-size: cover;
  background-position: center;
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
  width: 350PX;
  margin-left: 20px;
  margin: 5px
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
  margin-left: 20px
}

.namePost {
  font-size: 22px;
  font-family: 'Gilroy-Bold', sans-serif;
  margin: 0;
}

.subPost {
  font-size: 18px;
  font-family: 'Gilroy-Regular', sans-serif;
  margin: 0;
}

.subtitle {
  font-size: 12px;
  font-family: 'Gilroy-Regular', sans-serif;
  margin-bottom: 0;
  margin-top: 8px;
  align-items: flex-start
}

.subtitle-2 {
  font-size: 12px;
  font-family: 'Gilroy-Regular', sans-serif;
  margin-bottom: 2px;
  margin-top: 2px;
  align-items: flex-start
}

.linemain2 {
  border-bottom: 1px solid #ccc; /* Adiciona uma borda inferior cinza */
  margin-bottom: 10px; /* Adiciona espaço abaixo da linha */
}

.image-container {
  position: relative;
}

.image-info {
  position: absolute;
  display: flex;
  flex-direction: column;
  bottom: 0;
  left: 0;
  align-items: flex-start;
  color: white; /* Cor do texto */
  padding: 20px; /* Espaçamento interno */
}

.image-info-25 {
  position: absolute;

  display: flex;
  flex-direction: column;
  align-items: flex-start;
  bottom: 0;
  left: 0;
  color: white; /* Cor do texto */
  padding-left: 15px; /* Espaçamento interno */
  padding-bottom: 10px; /* Espaçamento interno */
}

@media screen and (max-width: 600px) {
  .wrapper {
    width: 100%;
  }

  .featured-box {
    width: 90%;
  }

  .img-50, .img-25 {
    height: auto;
    width: 100%;
  }

  .new, .newCronograma {
    flex-direction: column;
  }
}

</style>
