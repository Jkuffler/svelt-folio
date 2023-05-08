<script>
  const sections = ["About", "Experience", "Projects", "Contact"]
</script>

  <nav>
    {#each sections as section, i}
      <a href=#{section}> <button>{section}</button> </a>
    {/each}
  </nav>

<style>
  nav {
  }
</style>