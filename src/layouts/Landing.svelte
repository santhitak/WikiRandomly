<script lang="ts">
  import ToggleBtn from "@components/toggleBtn.svelte";
</script>

<section>
  <div class="container">
    <div class="contentWrapper">
      <h2>Random Wikipedia</h2>
      <form action="">
        <label for="wordSearch" />
        <input type="text" class="search" value="" />
      </form>
      <ToggleBtn />
    </div>

  </div>
</section>

<style>
  .container {
    width: 100vw;
    height: 100vh;
    background-color: var(--light);
    color: var(--dark);
    display: flex;
    justify-content: center;
  }
  .contentWrapper {
    width: 85%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }

  .search{
    padding: .5rem;
    width: 16rem;
  }

  .search::selection {
    font-weight: 600;
    font-family: "Open Sans", sans-serif;
    color: var(--light);
    background: var(--dark);
  }
</style>
