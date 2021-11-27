<script lang="ts">
  import Displayer from "@components/displayer.svelte";
  import BtnStyle from "@components/btnStyle.svelte";
</script>

<section>
  <div class="container">
    <div class="contentWrapper">
      <div class="searchWrapper">
        <h2>Random Wikipedia</h2>
        <form action="">
          <label for="wordSearch" />
          <input
            type="text"
            class="search"
            value=""
            placeholder="type something"
          />
        </form>
        <div>
          <BtnStyle />
          <button class="custom_btn">SEARCH</button>
          <button class="custom_btn">RANDOM</button>
        </div>
      </div>
    </div>
    <div class="contentWrapper">
      <Displayer />
    </div>
  </div>
</section>

<style>
  .container {
    width: 100vw;
    height: 100vh;
    background-color: var(--light);
    color: var(--dark);
    display: grid;
    justify-content: center;
    grid-template-columns: 25vw 75vw;
  }
  .contentWrapper {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .searchWrapper {
    height: 40vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;
  }

  .search {
    padding: 0.5rem;
    width: 16rem;
  }

  .search::selection {
    font-weight: 600;
    font-family: "Open Sans", sans-serif;
    color: var(--light);
    background: var(--dark);
  }
</style>
