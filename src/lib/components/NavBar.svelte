<script lang="ts">
  import { Link } from 'svelte-routing';

  export let isFixed: boolean = false;
</script>

<nav class="{isFixed ? 'fixed' : ''} top-0 left-0 w-full z-50 flex justify-center space-x-4 p-4">
  <Link to="/" class='text-white hover:underline '>HOME</Link>
      <Link to="/about" class='text-white hover:underline'>ABOUT</Link>
    <Link to="/projects" class='text-white hover:underline'>PROJECT</Link>
</nav>