<script lang="ts">
  import Card from "./Play/Card.svelte";
  const containerStyle =
    "flex flex-col min-h-screen items-center justify-center mx-auto px-2";
</script>

<main class={containerStyle}>
  <h1 class="font-bold text-2xl">Memory Game</h1>
  <br />
  <div class="flex flex-wrap gap-4 justify-center  lg:px-6">
    {#each { length: 24 } as _, i}
      <Card />
    {/each}
  </div>
</main>

<style>
  /* .card:hover {
    filter: drop-shadow(0 0 0.4em #747bff);
  } */

  /* .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00);
  } */
</style>
