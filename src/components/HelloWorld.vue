<template>
  <div>
    <!-- Navbar -->
    <b-navbar class="Navbar-Pokemon" type="dark">
      <b-navbar-nav class="navbar">
        <!-- Logo do site -->
        <img class="logomarca" src="../assets/img/logo.png" alt="Pokedex" />
        
        <b-nav-item href="#">Home</b-nav-item>
        <!-- Navbar dropdowns -->
        <b-nav-item-dropdown text="Geração Pokemon" right>
          <b-dropdown-item href="#" class="drop-geracao">Primeira Geração</b-dropdown-item>
          <b-dropdown-item href="#" class="drop-geracao">Segunda Geração</b-dropdown-item>
          <b-dropdown-item href="#" class="drop-geracao">Terceira Geração</b-dropdown-item>
          <b-dropdown-item href="#" class="drop-geracao">Quarta Geração</b-dropdown-item>
          <b-dropdown-item href="#" class="drop-geracao">Quinta Geração</b-dropdown-item>
          <b-dropdown-item href="#" class="drop-geracao">Sexta Geração</b-dropdown-item>
          <b-dropdown-item href="#" class="drop-geracao">Sétima Geração</b-dropdown-item>
          <b-dropdown-item href="#" class="drop-geracao">Oitava Geração</b-dropdown-item>
        </b-nav-item-dropdown>
      </b-navbar-nav>
    </b-navbar>

    <div>
      <section class="hero">
        <div class="hero-text-content">
          <h1>Welcome to Pokemon game list</h1>
          <p>
            Here you will find an application that consumes the PokeAPI API. It
            lists the Pokemon game generation, where some information is
            displayed: pokemon count by generation, main region, movements,
            species, etc...
          </p>
        </div>
        <img
          src="https://i.pinimg.com/originals/26/b5/55/26b5551ba10f013a335e91b98f530d51.png"
          alt="all pokemon image"
          class="heroPara"
        />
      </section>
    </div>
    <h2 class="mt-3">Gerações de Pokemon</h2>
    <section class="container mt-4">
      <div class="grid-card">
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
            <p class="card-text">Main region: Kanto</p>
            <p>
              Version groups: <br />
              red-blue <br />
              yellow
            </p>
            <button class="btn btn-secondary">Explore</button>
          </div>
          <div class="card-footer">
            <small class="text-muted">Last updated 3 mins ago</small>
          </div>
        </div>
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
            <p class="card-text">Main region: Kanto</p>
            <p>
              Version groups: <br />
              red-blue <br />
              yellow
            </p>
            <button class="btn btn-secondary">Explore</button>
          </div>
          <div class="card-footer">
            <small class="text-muted">Last updated 3 mins ago</small>
          </div>
        </div>
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
            <p class="card-text">Main region: John</p>
            <p>
              Version groups: <br />
              gold-silver <br />
              crystaL
            </p>
            <button class="btn btn-secondary">Explore</button>
          </div>
          <div>
            <div
              data-v-3b81dd4c=""
              class="poke-card__unit-stats poke-card__unit-stats--poke clearfix"
            >
              <div class="one-third-slash">
                <div class="stat">121</div>
                <div class="stat-value">Different moves</div>
              </div>
              <div class="one-third">
                <div class="stat">135</div>
                <div class="stat-value">Pokemon count</div>
              </div>
            </div>
          </div>
        </div>
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
            <p class="card-text">Main region: Hoenn</p>
            <p>
              Version groups: <br />
              ruby-sapphire <br />
              emerald <br />
              firered-leafgreen
            </p>
            <button class="btn btn-secondary">Explore</button>
          </div>
          <div class="card-footer">
            <small class="text-muted">Last updated 3 mins ago</small>
          </div>
        </div>
        <div class="card">
          <img
            class="card-img-top"
            data-src="holder.js/100px180/"
            alt="100%x180"
            src="https://www.serebii.net/pokemon/art/494.png"
            data-holder-rendered="true"
          />
          <div class="card-body">
            <h4 class="card-title">5ª Geração</h4>
            <p class="card-text">Main region: Sinnoh</p>
            <p>
              Version groups: <br />
              diamond-pearl <br />
              platinum <br />
              heartgold-soulsilver
            </p>
            <button class="btn btn-secondary">Explore</button>
          </div>
          <div class="card-footer">
            <small class="text-muted">Last updated 3 mins ago</small>
          </div>
        </div>
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
            <p class="card-text">Main region: Unova</p>
            <p>
              Version groups: <br />
              black-white <br />
              black-2-white-2
            </p>
            <button class="btn btn-secondary">Explore</button>
          </div>
          <div class="card-footer">
            <small class="text-muted">Last updated 3 mins ago</small>
          </div>
        </div>
        <div class="card">
          <img
            class="card-img-top"
            data-src="holder.js/100px180/"
            alt="100%x180"
            src="https://www.serebii.net/pokemon/art/650.png"
            data-holder-rendered="true"
          />
          <div class="card-body">
            <h4 class="card-title">7ª Geração</h4>
            <p class="card-text">Main region: Alola</p>
            <p>
              Version groups: <br />
              sun-moon <br />
              ultra-sun-ultra-moon <br />
              lets-go-pikachu-lets-go-eevee <br />
            </p>
            <button class="btn btn-secondary">Explore</button>
          </div>
          <div class="card-footer">
            <small class="text-muted">Last updated 3 mins ago</small>
          </div>
        </div>
        <div class="card">
          <img
            class="card-img-top"
            data-src="holder.js/100px180/"
            alt="100%x180"
            src="https://www.serebii.net/pokemon/art/650.png"
            data-holder-rendered="true"
          />
          <div class="card-body">
            <h4 class="card-title">8ª Geração</h4>
            <p class="card-text">Main region: Galar</p>
            <p>
              Version groups: <br />
              sword-shield
            </p>
            <button class="btn btn-secondary">Explore</button>
          </div>
          <div class="card-footer">
            <small class="text-muted">Last updated 3 mins ago</small>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>

export default {};
</script>

<style scoped>
/* Tamanho da logo */
.logomarca {
  max-width: 70px;
  margin-left: 10px;
}

/* Tamanho da Navbar e definições da fonte */
.navbar {
  display: flex;
  align-items: center;
  font-size: 23px;
  font-family: helvetica;
  height: 100px;
}

/* Cor da Navbar Cinza Escuro (#313131) */
.Navbar-Pokemon {
  background-color: #313131;
}

/* A fonte fica branca ao passar o mouse pelo menu, 0.5 seg de transição */
.Navbar-Pokemon :hover {
  color: white;
  transition: 0.5s;
}

/* Cor de fundo ao passar o mouse muda para cinza claro;
Cor da fonte muda para branco, 0,2s de transição */
.drop-geracao :hover{
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
}

.card-img-top {
  display: block;
  width: 15rem;
}

.btn {
  width: 150px;
}

.poke-card__unit-stats {
  color: #fff;
  font-weight: 700;
  border-bottom-left-radius: 14px;
  border-bottom-right-radius: 14px;
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
</style>
