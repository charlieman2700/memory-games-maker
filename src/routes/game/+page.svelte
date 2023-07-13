<script>
  import Card from "./components/Card.svelte";
</script>

<h1 class="mt-2 text-2xl font-bold">Memory Game</h1>

<main class={"text-center relative h-screen flex flex-col"}>
  <div class="  my-auto lg:px-2 flex flex-wrap gap-4 justify-center">
    {#each { length: 24 } as _}
      <Card />
    {/each}
  </div>
</main>
