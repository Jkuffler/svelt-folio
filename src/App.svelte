<script>
  import Nav from "./Nav.svelte"
  import About from "./routes/about/+page.svelte"
  import Tools from "./routes/tools/+page.svelte"
</script>

<main>
  <header><Nav /></header>
  <About />
  <Tools />
</main>

<style>
  header {
    position: sticky;
  }
</style>
