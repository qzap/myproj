<script>
  export let name;
</script>

<main>
  <h1>Hello {name}!</h1>
  <p>Hello, Ninjas!</p>
  <p>
    Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
    how to build Svelte apps.
  </p>
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  h1 {
    color: #810ECE;
    text-transform: lowercase;
    font-size: 4em;
    font-weight: 700;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
