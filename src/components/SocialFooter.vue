<template>
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
</template>

<script>
export default {
    name: 'SocialFooter',
}
</script>

<style scoped>
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