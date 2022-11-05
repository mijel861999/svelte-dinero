<script>
  let nombre = "Miguel";
  import Boton from "./components/Boton.svelte";
</script>

<main>
  <input type="text" bind:value={nombre} />
  <h1>Hola, {nombre}!</h1>
  <Boton />
</main>

<style>
  h1 {
    color: green;
  }
</style>
