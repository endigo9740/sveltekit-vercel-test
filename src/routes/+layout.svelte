<script>
  import "../app.postcss";
</script>

<svelte:head>
  <title>Sveltekit Vercel Test</title>
</svelte:head>

<nav class="flex space-x-4 mb-4">
  <a href="/">Homepage</a>
  <a href="/about">About</a>
</nav>
<slot />
