<template>
  <div>
    <menu-navbar />

    <div>
      <section class="hero">
        <div class="hero-text-content">
          <h1>Bem vindo ao Pokedex</h1>
          <p>
            Here you will find an application that consumes the PokeAPI API. It
            lists the Pokemon game generation, where some information is
            displayed: pokemon count by generation, Região, movements, species,
            etc...
          </p>
        </div>
        <img
          src="../../assets/img/herobg.png"
          alt="all pokemon image"
          class="heroPara"
        />
      </section>
    </div>

    <!-- Título que vai demonstrar os cards das gerações pokemons -->
    <div class="mid-division">
      <h1 class="mt-3">Gerações de Pokemon</h1>
    </div>

    <!-- Cards -->
    <section class="container mt-4">
      <div class="grid-card">
        <!-- Card Primeira Geração -->
        <div class="card">
          <img
            class="card-img-top"
            data-src="holder.js/100px180/"
            alt="100%x180"
            src="https://www.serebii.net/pokemon/art/001.png"
            data-holder-rendered="true"
          />
          <div class="card-body">
            <h4 class="card-title">1ª Geração</h4>
            <p class="card-text">Região: Kanto</p>
            <p class="card-versions">
              <b>Versões:</b> <br />
              Red-Blue <br />
              Yellow <br />
              Yellow
            </p>
            <button class="btn btn-secondary">Explorar</button>
          </div>
          <div>
            <div
              data-v-3b81dd4c=""
              class="poke-card__unit-stats poke-card__unit-stats--poke clearfix"
            >
              <div class="one-third-slash">
                <div class="stat">165</div>
                <div class="stat-value">Movimentos Diferentes</div>
              </div>
              <div class="one-third">
                <div class="stat">151</div>
                <div class="stat-value">Pokemons</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Card Segunda Geração -->
        <div class="card">
          <img
            class="card-img-top"
            data-src="holder.js/100px180/"
            alt="100%x180"
            src="https://www.serebii.net/pokemon/art/152.png"
            data-holder-rendered="true"
          />
          <div class="card-body">
            <h4 class="card-title">2ª Geração</h4>
            <p>Região: Johto</p>
            <p>
              <b>Versões:</b> <br />
              Gold-Silver <br />
              Crystal <br />
              Crystal
            </p>
            <button class="btn btn-secondary">Explorar</button>
          </div>
          <div>
            <div
              data-v-3b81dd4c=""
              class="poke-card__unit-stats poke-card__unit-stats--poke clearfix"
            >
              <div class="one-third-slash">
                <div class="stat">86</div>
                <div class="stat-value">Movimentos Diferentes</div>
              </div>
              <div class="one-third">
                <div class="stat">100</div>
                <div class="stat-value">Pokemons</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Card Terceira Geração -->
        <div class="card">
          <img
            class="card-img-top"
            data-src="holder.js/100px180/"
            alt="100%x180"
            src="https://www.serebii.net/pokemon/art/252.png"
            data-holder-rendered="true"
          />
          <div class="card-body">
            <h4 class="card-title">3ª Geração</h4>
            <p class="card-text">Região: Hoenn</p>
            <p>
              <b>Versões:</b> <br />
              Ruby-Sapphire <br />
              Emerald <br />
              FireRed-LeafGreen
            </p>
            <button class="btn btn-secondary">Explorar</button>
          </div>
          <div>
            <div
              data-v-3b81dd4c=""
              class="poke-card__unit-stats poke-card__unit-stats--poke clearfix"
            >
              <div class="one-third-slash">
                <div class="stat">121</div>
                <div class="stat-value">Movimentos Diferentes</div>
              </div>
              <div class="one-third">
                <div class="stat">135</div>
                <div class="stat-value">Pokemons</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Card Quarta Geração -->
        <div class="card">
          <img
            class="card-img-top"
            data-src="holder.js/100px180/"
            alt="100%x180"
            src="https://www.serebii.net/pokemon/art/387.png"
            data-holder-rendered="true"
          />
          <div class="card-body">
            <h4 class="card-title">4ª Geração</h4>
            <p class="card-text">Região: Sinnoh</p>
            <p>
              <b>Versões:</b> <br />
              Diamond-Pearl <br />
              Platinum <br />
              HeartGold-SoulSilver
            </p>
            <button class="btn btn-secondary">Explorar</button>
          </div>
          <div>
            <div
              data-v-3b81dd4c=""
              class="poke-card__unit-stats poke-card__unit-stats--poke clearfix"
            >
              <div class="one-third-slash">
                <div class="stat">113</div>
                <div class="stat-value">Movimentos Diferentes</div>
              </div>
              <div class="one-third">
                <div class="stat">107</div>
                <div class="stat-value">Pokemons</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Card Quinta Geração -->
        <div class="card">
          <img
            class="card-img-top"
            data-src="holder.js/100px180/"
            alt="100%x180"
            src="https://www.serebii.net/pokemon/art/495.png"
            data-holder-rendered="true"
          />
          <div class="card-body">
            <h4 class="card-title">5ª Geração</h4>
            <p class="card-text">Região: Unova</p>
            <p>
              <b>Versões:</b> <br />
              Black-White <br />
              Black2-White2 <br />
              Black-White
            </p>
            <button class="btn btn-secondary">Explorar</button>
          </div>
          <div>
            <div
              data-v-3b81dd4c=""
              class="poke-card__unit-stats poke-card__unit-stats--poke clearfix"
            >
              <div class="one-third-slash">
                <div class="stat">92</div>
                <div class="stat-value">Movimentos Diferentes</div>
              </div>
              <div class="one-third">
                <div class="stat">156</div>
                <div class="stat-value">Pokemons</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Card Sexta Geração -->
        <div class="card">
          <img
            class="card-img-top"
            data-src="holder.js/100px180/"
            alt="100%x180"
            src="https://www.serebii.net/pokemon/art/650.png"
            data-holder-rendered="true"
          />
          <div class="card-body">
            <h4 class="card-title">6ª Geração</h4>
            <p class="card-text">Região: Kalos</p>
            <p>
              <b>Versões:</b> <br />
              X-Y <br />
              OmegaRuby-AlphaSapphire <br />
              X-Y
            </p>
            <button class="btn btn-secondary">Explorar</button>
          </div>
          <div>
            <div
              data-v-3b81dd4c=""
              class="poke-card__unit-stats poke-card__unit-stats--poke clearfix"
            >
              <div class="one-third-slash">
                <div class="stat">62</div>
                <div class="stat-value">Movimentos Diferentes</div>
              </div>
              <div class="one-third">
                <div class="stat">72</div>
                <div class="stat-value">Pokemons</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Card Sétima Geração -->
        <div class="card">
          <img
            class="card-img-top"
            data-src="holder.js/100px180/"
            alt="100%x180"
            src="https://www.serebii.net/pokemon/art/722.png"
            data-holder-rendered="true"
          />
          <div class="card-body">
            <h4 class="card-title">7ª Geração</h4>
            <p class="card-text">Região: Alola</p>
            <p>
              <b>Versões:</b> <br />
              Sun-Moon <br />
              UltraSun-UltraMoon <br />
              Let's Go Pikachu- Let's go Eevee
            </p>
            <button class="btn btn-secondary">Explorar</button>
          </div>
          <div>
            <div
              data-v-3b81dd4c=""
              class="poke-card__unit-stats poke-card__unit-stats--poke clearfix"
            >
              <div class="one-third-slash">
                <div class="stat">121</div>
                <div class="stat-value">Movimentos Diferentes</div>
              </div>
              <div class="one-third">
                <div class="stat">88</div>
                <div class="stat-value">Pokemons</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Card Oitava Geração -->
        <div class="card">
          <img
            class="card-img-top"
            data-src="holder.js/100px180/"
            alt="100%x180"
            src="https://www.serebii.net/pokemon/art/810.png"
            data-holder-rendered="true"
          />
          <div class="card-body">
            <h4 class="card-title">8ª Geração</h4>
            <p class="card-text">Região: Galar</p>
            <p>
              <b>Versões:</b> <br />
              Sword-Shield <br />
              Sword-Shield <br />
              Sword-Shield <br />
            </p>
            <button class="btn btn-secondary">Explorar</button>
          </div>
          <div>
            <div
              data-v-3b81dd4c=""
              class="poke-card__unit-stats poke-card__unit-stats--poke clearfix"
            >
              <div class="one-third-slash">
                <div class="stat">84</div>
                <div class="stat-value">Movimentos Diferentes</div>
              </div>
              <div class="one-third">
                <div class="stat">89</div>
                <div class="stat-value">Pokemons</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer id="footer"> 
      <div class="footer-content">
        <h3>Pokedex</h3>
        <p>A melhor forma de classificar seus pokemons.</p>
        <ul class="social">
          <li><a href="https://twitter.com/pokemon" target="_blank"><font-awesome-icon icon="fa-brands fa-twitter" /></a></li>
          <li><a href="https://www.facebook.com/Pokemon/" target="_blank"><font-awesome-icon icon="fa-brands fa-facebook" /></a></li>
          <li><a href="https://www.instagram.com/pokemon/" target="_blank"><font-awesome-icon icon="fa-brands fa-instagram" /></a></li>  
        </ul>
      </div>
      <div class="footer-bottom">
          <p>Pokedex &copy; 2022</p>
      </div>
    </footer>
  </div>
</template>

<script>
import navbar from "../MenuNavbar";

export default {
  components: {
    "menu-navbar": navbar,
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

.grid-card {
  width: 100%;
  display: grid;
  grid-template-columns: repeat(auto-fit, 310px);
  place-content: center;
  gap: 1.5rem 4rem;
  justify-items: center;
  align-items: self-start;
}

h4 {
  font-weight: bold;
}

.card {
  min-width: 330px;
  min-height: 542px;
  align-items: center;
  box-shadow: rgba(0, 0, 0, 0.25) 0px 14px 28px,
    rgba(0, 0, 0, 0.22) 0px 10px 10px;

  border-bottom-left-radius: 13px;
  border-bottom-right-radius: 13px;

  /* Borda do Card 0px e cor da borda do card transparente para evitar bordas brancas */
  border: 0px;
  border-color: transparent;
}

.card-img-top {
  display: block;
  width: 15rem;
}

/* Tamanho do botão explorar */
.btn {
  width: 300px;
}

.poke-card__unit-stats {
  color: #fff;
  font-weight: 700;
  /* Border radius 13px igual o do card para evitar bordas brancas */
  border-bottom-left-radius: 13px;
  border-bottom-right-radius: 13px;
}

.poke-card__unit-stats .one-third {
  width: 50%;
  float: left;
  padding: 25px 27px;
}
.poke-card__unit-stats--poke {
  background: #5f5f5f;
}

.poke-card__unit-stats .one-third-slash {
  width: 50%;
  float: left;
  padding: 25px 27px;
  border-right: 1px solid #2b3341;
}

/* Define a cor de fundo do footer, altura e alinhamento do texto */
#footer {
  background-color: #313131;
  color: white;
  margin-top: 30px;
  height: auto;
  padding-top: 30px;
}

.footer-content{
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  text-align: center;
}

.footer-content h3{
  font-size: 1.8rem;
  font-weight: 400;
  text-transform: capitalize;
  line-height: 3rem;
}

.footer-content p{
  max-width: 500px;
  margin: 10px, auto;
  line-height: 28px;
  font-size: 14px;
}

.social{
  list-style: none;
  display: flex;
  padding: 0;
  align-items: center;
  justify-content: center;
  
}

.social li{
  margin: 10px;
  
}

.social a{
  text-decoration: none;
  color: #fff;
  font-size: 30px;
}

.social a:hover {
  color:rgb(238, 255, 2);
  
}

.footer-bottom{
  background: black;
  width: 100%;
  padding: 20px;
  text-align: center;
  justify-content: center;
  margin: 0;
}

.footer-bottom p{
  font-size: 14px;
  word-spacing: 2px;
  text-transform: capitalize;

}

</style>
