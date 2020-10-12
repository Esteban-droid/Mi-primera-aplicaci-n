<template>
  <div>
    <div class="Bienvenida">
      Bienvenido, nombre de persona
    </div>
    <header>
      <nav>
        <center>
          <span><a href="#">Home</a></span> |
          <span><a href="#">Mis Libros</a></span> |
          <span><a href="#">Buscar Libros</a></span> |
          <span><a href="#">Salir</a></span> |
        </center>
      </nav>
    </header>
    <h1>Mi aplicación en progreso</h1>
    <pre>Lorem ipsum dolor sit amet consectetur, adipiscing
      elit porttitor ultricies per, litora mollis justo urna.
      Suscipit habitasse est quis erat imperdiet interdum
      facilisis, congue praesent neque gravida tincidunttt.</pre>
    <table style="width:100%">
      <caption>Tus últimos libros</caption>
      <tr>
        <th>Nombre de Libro</th>
        <th>Nombre de Autor</th>
      </tr>
      <tr>
        <td>Libro 1</td>
        <td>Autor 1</td>
      </tr>
      <tr>
        <td>Libro 2</td>
        <td>Autor 2</td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {
name: "Principal"
}
</script>

<style scoped>
  h1{
    margin: 50px 0 0;
    background-color: #005eff;
    color: #00ff37;
  }
  .Bienvenida{
    width: 100%;
    text-align: center;
    position: absolute;
    top: 30px;
  }
</style>