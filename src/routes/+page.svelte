<script lang="ts">
  import SplashScreen from "./components/SplashScreen.svelte";
</script>

<div
  class="bg-[#9BDFFE] min-h-screen flex-col justify-center flex items-center"
>
  <SplashScreen />
  <nav class=" mt-10">
    <li>
      <a href="/gameMaker">Administrador de juegos</a>
    </li>
    <li>
      <a href="/game">Modo Juego</a>
    </li>
  </nav>
</div>
