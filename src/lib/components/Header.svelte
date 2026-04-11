<script lang="ts">
  import { page } from '$app/stores';
  import List from '~icons/custom/list';
  import Closed from '~icons/custom/closed';
  let isHamburgerMenuOpen = false;
</script>

<header class="px-8 md:px-16 bg-neutral-50 sticky top-0 z-40">
  <div
    class="w-full flex py-4 items-center justify-between border-b border-gray-600 h-[80px]"
  >
    <a href="/">
      <figure>
        <img alt="Paly Logo" src="/paly.png" height="65" width="65" />
      </figure>
    </a>
    <!-- Empieza: Menu derecha-->
    <nav class="hidden md:inline-block">
      <a
        class="nav-item"
        href="/coleccion"
        class:active-nav-item={$page.url.pathname.startsWith('/coleccion')}
        >Colección</a
      >
      <a
        class="nav-item"
        href="/lab"
        class:active-nav-item={$page.url.pathname.startsWith('/lab')}>Lab</a
      >
      <a
        class="nav-item"
        href="/acerca"
        class:active-nav-item={$page.url.pathname.startsWith('/acerca')}
        >Acerca</a
      >
    </nav>

    <!-- Termina: Menu derecha -->
    <!-- Empieza: Menu Hamburguesa -->
    <button
      on:click={() => (isHamburgerMenuOpen = true)}
      class="md:hidden bg-neutral-50"
    >
      <List />
    </button>
    {#if isHamburgerMenuOpen}
      <div
        class="md:hidden bg-neutral-50 fixed top-0 left-0 flex flex-col h-screen w-screen z-10"
      >
        <div class="p-4">
          <button on:click={() => (isHamburgerMenuOpen = false)}>
            <Closed />
          </button>
        </div>
        <ul class="flex flex-col space-y-4 items-center p-4 w-full h-full">
          <li class="text-center w-full">
            <a
              on:click={() => (isHamburgerMenuOpen = false)}
              class="nav-item nav-item-mobile"
              href="/coleccion"
              class:active-nav-item={$page.url.pathname.startsWith(
                '/coleccion'
              )}>Colección</a
            >
          </li>
          <li class="text-center w-full">
            <a
              on:click={() => (isHamburgerMenuOpen = false)}
              class="nav-item nav-item-mobile"
              href="/galeria"
              class:active-nav-item={$page.url.pathname.startsWith('/galeria')}
              >Galería</a
            >
          </li>
          <li>
            <a
              on:click={() => (isHamburgerMenuOpen = false)}
              class="nav-item nav-item-mobile"
              href="/lab"
              class:active-nav-item={$page.url.pathname.startsWith('/lab')}
              >Lab</a
            >
          </li>
          <li class="text-center w-full">
            <a
              on:click={() => (isHamburgerMenuOpen = false)}
              class="nav-item nav-item-mobile"
              href="/acerca"
              class:active-nav-item={$page.url.pathname.startsWith('/acerca')}
              >Acerca</a
            >
          </li>
        </ul>
      </div>
    {/if}
    <!-- Termina: Menu Hamburguesa -->
  </div>
</header>

<style>
  .nav-item {
    padding: 8px 28px;
    height: 40px;
    border-radius: 20px;
    font-size: 14px;
    font-weight: 400;
    position: relative;
    cursor: pointer;
  }

  .active-nav-item {
    font-weight: bold;
    color: #121212;
    z-index: 2;
  }

  .active-nav-item::before {
    background-color: transparent;
    content: '';
    top: 3px;
    position: absolute;
    left: 3px;
    width: 100%;
    height: 100%;
  }
</style>
