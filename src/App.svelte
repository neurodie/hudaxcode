<script lang="ts">
  import { Router, Route } from 'svelte-routing';
  import Home from './routes/Home.svelte';
  import About from './routes/About.svelte';
  import Projects from './routes/Projects.svelte';
 import NotFound from './routes/NotFound.svelte';
</script>

<main>
  <Router>

    <Route path="/" component={Home} />
    <Route path="/about" component={About} />
    <Route path="/projects" component={Projects} />
   <Route component={NotFound} />

  </Router>
</main>