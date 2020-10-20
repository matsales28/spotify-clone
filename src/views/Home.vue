<template>
<div class="container-fluid" id="telaInteira">
    <div class="home">

        <div class="landing-text" id="anuncio">
            <H1> Escutar <br>muda tudo</H1>
            <p>Milhões de músicas e podcasts para explorar. E nem precisa de cartão de crédito.</p>
            <a href="#" class="btn btn-success btn-lg" id="button"> OBTENHA O SPOTIFY FREE </a>

        </div>
        <img src="../../assets/home.svg" class="img-fluid " alt="Imagem responsiva">
    </div>
</div>
</template>

<script>
</script>

<style lang="scss">

  div#telaInteira {
      background-color: #1414ebea;
      width: 100%;
      height: 100%;
  }
  
  .home {
      display: flex;
      align-items: center;
      justify-content: center;
      padding-top: 10em;
  }
  
  @media (max-width: 800px) {
      .home img {
          display: none;
      }
  }
  
  .home img {
      justify-content: center;
      max-width: 40rem;
  }
  
  .home div#anuncio {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding-right: 2rem;
  }
  
  .home div#anuncio>h1 {
      font-family: 'Secular One', sans-serif;
      font-size: 7em;
      text-align: center;
      color: #1ED760;
  }
  
  .home div#anuncio>p {
      padding-top: 0.5rem;
      color: #1ED760;
  }
  
  body {
      font-family: 'Courier Prime', monospace;
      font-family: 'Roboto', sans-serif;
  }
  
  a#button {
      border-radius: 10em;
      flex-direction: row;
      font-size: 1rem;
      margin-top: 2rem;
      margin-bottom: 2rem;
  }

</style>
