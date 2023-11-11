<script>
  import '../style.css'
  import '@fontsource/inter'
  import '@fontsource/roboto'
</script>

<head>

</head>

<header class="flex">
  <div class="flex perfil">
    <a href="/" title="ir a perfil">
      <img src="https://i.pinimg.com/236x/04/02/f9/0402f9cebec8108fc2ebdf7d1c71b65c.jpg" alt="" width="44">
    </a>
    <a href="/" title="Inicio">miPagina</a>
  </div>
  <nav>
    <ul class="flex">
      <li><a href="/">About</a></li>
      <li><a href="/">Work</a></li>
      <li><a href="/">Blog</a></li>
      <li><a href="/">Store</a></li>
    </ul>
  </nav>
  <a class="contact" href="google.com">Contact</a>
</header>

<style>
  .flex {
    display: flex;
  }
  header {
    justify-content: space-between;
    align-items: center;
  }
  nav {
    border: 1px solid rgba(204, 204, 204, 0.607);
    border-radius: 24px;
    padding: 14px 24px;
  }
  ul {
    list-style: none;
    gap: 16px;
  }
  img {
    border-radius: 22px;
  }
  a {
    text-decoration: none;
    color: black; 
    font-weight: bold;
  }
  .contact {
    border: 1px solid orange;
    border-radius: 50px;
    padding: 10px 15px;
    background-color: rgb(255, 89, 0);
    color: white;
    font-weight: 100;
  }
  .perfil {
    align-items: center;
    gap: 10px;
  }
</style>
<slot />