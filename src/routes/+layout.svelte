<script>
    import "../app.css";
    import Home from './Home.svelte';
    import Dashboard from './Dashboard.svelte';
  </script>

 
 <main>
  <!-- Use the Home component here -->
  <Home />
<Dashboard />
  <!-- The rest of your content or routes can go here -->
  <slot />
</main>


 