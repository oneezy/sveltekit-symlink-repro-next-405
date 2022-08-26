<header>
  <code>✅ 1.0.0-next.405</code>
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
  code { background: black; color: white; border-radius: 100px; padding: .5rem 1rem; display: inline-block; }
</style>