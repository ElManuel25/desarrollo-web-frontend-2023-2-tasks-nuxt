<template>
  <div>
    <center>
      <h1>Bienvenidos a la app de tareas</h1>
      <p>Esta es una aplicación que permite gestionar las tareas de los estudiantes</p>

      <a href="/tareas">Click para iniciar (sin nuxtLink)</a>
<br>
<br>
<NuxtLink to="/tareas">
        Ir a app de tareas (con nuxtLink)</NuxtLink>
<br>
<br>

      <NuxtLink to="/">
        Ir a Inicio de Sesión</NuxtLink>
    </center>

  </div>


</template>



<script>
definePageMeta({
  layout: "blank",
});
</script>

