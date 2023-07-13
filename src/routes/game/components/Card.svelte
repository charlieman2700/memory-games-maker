<script>
  let isHidden = true;
</script>

<div class="card w-[90px] h-[130px] lg:h-[150px] lg:w-[110px]">
  {#if isHidden}
    <img
      class="backImage"
      src="/pattern.jpg"
      alt=""
      height="100%"
      width="100%"
    />
  {:else}
    <img src="/estrellaTest.avif" alt="" height="100%" width="100%" />
  {/if}
</div>

<style>
  .backImage {
    border-radius: 10px;
  }

  .card {
    overflow: hidden;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    border-radius: 10px;
    border: #747bff solid 2px;
    box-shadow: 5px 5px 5px 0px rgba(0, 0, 0, 0.44);
  }
</style>
