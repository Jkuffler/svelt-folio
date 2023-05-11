<script>
  import { Router, Route } from "svelte-routing"
  import { navigate } from "svelte-routing"

  const handleNavClick = page => {
    navigate(page)
  }
</script>

<nav>
  <Router>
    <Route> 
      <button on:click={handleNavClick}><a href="/">Home</a></button>
    </Route>
    <Route> 
      <button on:click={handleNavClick}><a href="/About">About</a></button>
    </Route>    
    <Route> 
      <button on:click={handleNavClick}><a href="/Tools">Tools</a></button>
    </Route>
  </Router>
</nav>
<!-- <nav>
  <Router>
    <Route component={About} />
    <Route component={Tools} />
  </Router>
</nav> -->
<!--   <button on:click={handleNavClick("/About")}><a href="/About">About</a></button>
  <button on:click={handleNavClick("/Tools")}><a href="/Tools">Tools</a></button>
  <button><a href="/projects">projects</a></button>
  <button><a href="/contact">contact</a></button> -->
<style>
</style>
