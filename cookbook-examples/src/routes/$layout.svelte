<script>
</script>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
      Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  }

  ul {
    list-style: none;
    font-size: 2rem;
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    justify-content: space-evenly;
  }

  main {
    max-width: 960px;
    margin: 0 auto;
  }
</style>

<nav>
  <ul>
    <li><a href="/">Index</a></li>
    <li><a href="/cookbook">Cookbook</a></li>
  </ul>
</nav>
<main>
  <slot />
</main>
