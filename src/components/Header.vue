<template>
  <div id="header">
    <div id="content_header">
      <nav>
        <img src="../assets/logo_branca.jpg" alt="Logo da Empresa" id="logo">
        <div class="nav-container">
          <a href="#" class="nav-item">games</a>
          <a href="#new" class="nav-item">notícias</a>
          <a href="#cronogramaPage" class="nav-item">cronograma</a>
        </div>
      </nav>
      <div id="presentation">
        <div id="text_presentation">
          <p id="text_1">SEU GAME</p>
          <p id="text_2">FAVORITO</p>
          <p id="text_3">veja abaixo as mais novas notícias e não perca nenhuma novidade</p>
        </div>
        <button id="news_button">novidades</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderPage'
}
</script>

<style scoped>
html, body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

* {
  padding: 0;
  margin: 0;
}

#header {
  background-image: url(../assets/fundo_header.jpg);
  background-position: center center;
  width: 100%;
  height: 50rem;
  margin-top: 0;
}

#content_header {
  justify-content: center;
  align-items: center; 
  padding: 3rem;
  margin: -4rem 8.375rem 0 8.375rem;
}

nav {
  display: flex;
  align-items: center;
  height: 3.125rem;
  gap: 11.25rem;
}

.nav-container {
  display: flex;
}

.nav-item {
  color: white; 
  margin: 0 1.25rem; 
  position: relative; 
  padding: 0.625rem 0; 
  font-size: 1.875rem;
  font-weight: bold;
  text-decoration: none;
}

.nav-item:hover, .nav-item:focus {
  color: #0076EA;
  transition: 0.2s;
}

.nav-item::after {
  content: ""; 
  position: absolute;
  bottom: 0; 
  left: 0;
  width: 100%;
  height: 0.125rem; 
  background-color: #0A7AE5;
}

#presentation {
  width: 30.625rem;
  height: 22.5rem;
  display: flex;
  flex-direction: column;
  justify-content: space-between; 
  font-weight: bold;
  font-size: 4.375rem;
  color: white;
  margin-top: 12.5rem;
  margin-left: -3.75rem;
}

#text_presentation :nth-child(2) {
  font-size: 4.6875rem;
  background: -webkit-linear-gradient(left, #0A7AE5, #04F460);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

#text_presentation :nth-child(3) {
  font-size: 1.5625rem;
}

#news_button {
  background-image: linear-gradient(to right,#0A7AE5, #04F460);
  width: 24.6875rem;
  height: 6.75rem;
  font-size: 4.375rem;
  font-weight: bold;
  border: none;
  border-radius: 2.625rem;
  margin: 0 auto;
  color: white;
}

/* Media queries for responsiveness */
@media screen and (max-width: 1200px) {
  #presentation {
    font-size: 3.5rem;
  }

  .nav-item {
    font-size: 1.5rem;
  }

  #news_button {
    width: 20rem;
    height: 5.5rem;
    font-size: 3.5rem;
  }
}

@media screen and (max-width: 900px) {
  #presentation {
    font-size: 3rem;
  }

  .nav-item {
    font-size: 1.2rem;
  }

  #news_button {
    width: 18rem;
    height: 5rem;
    font-size: 3rem;
  }
}

@media screen and (max-width: 600px) {
  #presentation {
    font-size: 2.5rem;
  }

  .nav-item {
    font-size: 1rem;
  }

  #news_button {
    width: 16rem;
    height: 4.5rem;
    font-size: 2.5rem;
  }
}
</style>