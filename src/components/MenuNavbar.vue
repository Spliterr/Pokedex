<template>
  <!-- Navbar -->
  <b-navbar class="Navbar-Pokemon" type="dark">
    <b-navbar-nav class="navbar">
      <!-- Logo do site -->
      <img class="logomarca" src="../assets/img/logo.png" alt="Pokedex" />

      <b-nav-item href="#">Home</b-nav-item>
      <!-- Navbar dropdowns -->
      <b-nav-item-dropdown text="Geração Pokemon" right>
        <b-dropdown-item href="#" class="drop-geracao"
          >Primeira Geração</b-dropdown-item
        >
        <b-dropdown-item href="#" class="drop-geracao"
          >Segunda Geração</b-dropdown-item
        >
        <b-dropdown-item href="#" class="drop-geracao"
          >Terceira Geração</b-dropdown-item
        >
        <b-dropdown-item href="#" class="drop-geracao"
          >Quarta Geração</b-dropdown-item
        >
        <b-dropdown-item href="#" class="drop-geracao"
          >Quinta Geração</b-dropdown-item
        >
        <b-dropdown-item href="#" class="drop-geracao"
          >Sexta Geração</b-dropdown-item
        >
        <b-dropdown-item href="#" class="drop-geracao"
          >Sétima Geração</b-dropdown-item
        >
        <b-dropdown-item href="#" class="drop-geracao"
          >Oitava Geração</b-dropdown-item
        >
      </b-nav-item-dropdown>
    </b-navbar-nav>
  </b-navbar>
</template>

<script>

</script>


<style>
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
</style>
