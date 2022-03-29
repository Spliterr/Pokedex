<template>
  <div>
    <menu-navbar />
    <hero-text />
    
    <!-- Título que vai demonstrar os cards das gerações pokemons -->
    <sub-hero-text text="Gerações de Pokemon"/>

    <!-- Cards -->
    <section class="container mt-4">
      <poke-card />
    </section>

    <!-- Footer -->
    <social-footer />
  </div>
</template>

<script>
import navbar from "../components/MenuNavbar.vue";
import herotext from "../components/HeroText.vue";
import pokecard from "../components/PokeCard.vue";
import socialfooter from "../components/SocialFooter.vue";
import subherotext from "../components/SubHeroText.vue";

export default {

  name: 'IndexMain',

  components: {
    "menu-navbar": navbar,
    "hero-text": herotext,
    "poke-card": pokecard,
    "social-footer": socialfooter,
    "sub-hero-text": subherotext,
  },
};
</script>

<style scoped>
/* Cor de fundo ao passar o mouse muda para cinza claro;
Cor da fonte muda para branco, 0,2s de transição */
.drop-geracao :hover {
  background-color: #616161;
  transition: 0.18s;
  color: white;
}

.container {
  z-index: 1;
  position: relative;
}

</style>
