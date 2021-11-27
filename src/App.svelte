<script lang="ts">
  import Landing from "@layouts/Landing.svelte";
</script>

<main>
  <Landing />
</main>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;500;600;700&display=swap");
  :root {
    font-family: "Open Sans", sans-serif;
    -webkit-font-smoothing: antialiased;

    --dark: #222327;
    --light: #ececee;
  }
  :global(section) {
    max-height: 100vh;
    max-width: 100vw;
  }
</style>
