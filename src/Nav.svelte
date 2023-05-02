<script>
  const sections = ["About", "Experience", "Projects", "Contact"]
</script>

<header>
  <nav>
    {#each sections as section, i}
      <a href={section}> <button>{section}</button> </a>
    {/each}
  </nav>
</header>

<style>
  * {
    display: grid;
  }
</style>