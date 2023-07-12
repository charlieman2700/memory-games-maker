<script lang="ts">
  import Card from "$lib/components/Card.svelte";
</script>

<main class={"text-center relative h-screen flex flex-col"}>
  <h1 class="mt-2 text-2xl font-bold">Memory Game</h1>
  <div class="  my-auto lg:px-2 cards-container">
    {#each { length: 24 } as _}
      <Card />
    {/each}
  </div>
</main>

<style>
  .cards-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1rem;
  }
</style>
