<template>
  <div>
    <section class="hero">
      <div class="hero-text-content">
        <h1>Bem vindo ao Pokedex</h1>
        <p>
          Aqui você encontrará uma aplicação que consome a API PokeAPI. Ela
          lista as geraçãoes do jogo Pokémon, onde algumas informações são
          exibidas: contagem de pokémons por geração, Região, movimentos,
          espécies, etc...
        </p>
      </div>
      <img
        src="../assets/img/herobg.png"
        alt="all pokemon image"
        class="heroPara"
      />
    </section>
  </div>
</template>
        
<script>
  export default{
    name: 'HeroText',
  }
</script>

<style scoped>
.hero {
  text-align: center;
  height: 45vh;
  overflow: hidden;
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
}

.hero-text-content {
  display: grid;
  max-width: 60%;
}

.hero img {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 1500px;
  min-width: 100%;
  min-height: 100%;
  transition: 1ms;
  filter: blur(2px);
  z-index: -1;
}

</style>
