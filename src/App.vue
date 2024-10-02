<template>
  <div>
    <header>
      <h1>Visua</h1>
      <nav>
        <ul>
          <li><a href="#sobre">Sobre</a></li>
          <li><a href="#projetos">Projetos</a></li>
          <li><a href="#contato">Contato</a></li>
        </ul>
      </nav>
    </header>

    <section id="sobre" class="intro">
      <h2>Sobre Nós</h2>
      <img src="./assets/perfil.jpg" class="perfil" alt="Perfil">
      <p>Visua é uma aplicação para pessoas com deficiência visual...</p>
    </section>

    <section id="projetos" class="galeria">
      <h2>Meus Projetos</h2>
      <div class="grid-container">
        <div class="grid-item">
          <img src="./assets/projeto1.jpg" alt="Projeto 1">
          <p>Projeto 1: Website</p>
        </div>
        <div class="grid-item">
          <img src="./assets/projeto2.jpg" alt="Projeto 2">
          <p>Projeto 2: Aplicativo</p>
        </div>
        <div class="grid-item">
          <img src="./assets/projeto3.jpg" alt="Projeto 3">
          <p>Projeto 3: Smartwatch</p>
        </div>
      </div>
    </section>

    <footer>
      <p>Entre em contato: <a href="mailto:email@example.com">visua@gmail.com</a></p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style scoped>
@import '../styles.css';
</style>

<template>
  <div>
      <header class="header">Meu Portfólio</header>
      <main>
          <router-view></router-view>
      </main>
      <footer class="footer">© 2024 Meu Nome. Todos os direitos reservados.</footer>
  </div>
</template>

<style scoped>
.footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 20px 0;
  position: relative;
  bottom: 0;
  width: 100%;
}
</style>

