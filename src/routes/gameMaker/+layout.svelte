<script>
  import DesktopMenu from "./DesktopMenu.svelte";
  import MobileMenu from "./MobileMenu.svelte";
  import NavBar from "./NavBar.svelte";
</script>

<div class="min-h-full">
  <NavBar />

  <header class="bg-white shadow-sm">
    <div class="mx-auto max-w-7xl px-4 py-4 sm:px-6 lg:px-8">
      <h1 class="text-lg font-semibold leading-6 text-gray-900">Dashboard</h1>
    </div>
  </header>
  
  <main>
    <div class="mx-auto max-w-7xl py-6 sm:px-6 lg:px-8">
      <!-- Your content -->
      <slot />
    </div>
  </main>
</div>
