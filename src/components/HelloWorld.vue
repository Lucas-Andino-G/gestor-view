<template>
  <div class="hello">
    <h1 >{{ msg }}</h1>
    
    <h3></h3><br>
    <!-- <ul>
      <li><strong>Agregar Tarea:</strong> Permite ingresar nuevas tareas manualmente.</li><br><br>
      <li><strong>Listar de Tareas:</strong> Muestra todas las tareas extraídas desde la API, permitiendo marcarlas como completadas o eliminarlas.</li><br><br>
      <li><strong>Vista Combinada:</strong>Combina las funcionalidades de añadir tareas manualmente y ver las tareas de la API al mismo tiempo.</li>      
    </ul>    -->
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
  font-weight: bold;
  color: rgb(44, 8, 163);
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
h1 {
  color: rgb(4, 4, 57);
  font-weight: bold;
}
</style>
