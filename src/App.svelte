<script>
  import svelteLogo from './assets/svelte.svg'
  import shagohod from './assets/shagohod_transp.png'
</script>

<main>
  <div>

    <h1 id="title">SHAGOHOD.NET</h1>

    <img id="shagohod" src={shagohod} alt="shagohod"/>

    <a href="https://vitejs.dev" target="_blank" rel="noreferrer"> 
      <img src="/vite.svg" class="logo" alt="Vite Logo" />
    </a>
    <a href="https://svelte.dev" target="_blank" rel="noreferrer"> 
      <img src={svelteLogo} class="logo svelte" alt="Svelte Logo" />
    </a>
  </div>
  
  <h1>Vite + Svelte</h1>

  <p>
    Check out <a href="https://github.com/sveltejs/kit#readme" target="_blank" rel="noreferrer">SvelteKit</a>, the official Svelte app framework powered by Vite!
  </p>

  <p class="read-the-docs">
    Click on the Vite and Svelte logos to learn more
  </p>
</main>

<style>

  #title {
    font-family: MetalGear;
    font-size: 5em;
    letter-spacing: 0.1em;
    text-decoration: underline;
    font-weight: lighter;
    margin-left: auto;
    margin-right: auto;
    margin-bottom: 0;
  }

  #shagohod {
    display: block;
    max-width: 75%;
    margin-left: auto;
    margin-right: auto;
  }

  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .read-the-docs {
    color: #888;
  }
</style>
