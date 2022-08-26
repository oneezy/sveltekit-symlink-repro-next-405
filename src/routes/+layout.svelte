<header>
  <a class="github" href="https://github.com/oneezy/sveltekit-symlink-repro-next-431">✅ 1.0.0-next.431</a>
  <nav>
    <a href="/">Home</a>
    <a href="/normal">Normal Route</a>
    <a href="/symlink">Symlink Route</a>
  </nav>
</header>

<slot />

<style>
  header { display: flex; flex-direction: column; align-items: center; gap: 1rem; }
  nav { display: flex; align-items: center; justify-content: center; gap: 1rem; margin: 0 auto; }
  a.github { font-family: monospace; background: black; color: white; border-radius: 100px; padding: .5rem 1rem; display: inline-block; text-decoration: none; }
</style>