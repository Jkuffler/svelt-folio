<script>
  const sections = ["About", "Tools", "Projects", "Contact"]
</script>

<nav>
  {#each sections as section, i}
    <a href="#{section}"> <button>{section}</button> </a>
  {/each}
</nav>

<style>
  nav {
    position: sticky;
  }
</style>
