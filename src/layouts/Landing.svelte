<script lang="ts">
  import Displayer from "@components/displayer.svelte";
  import BtnStyle from "@components/btnStyle.svelte";
  import Logo from "@assets/logo.svelte";
</script>

<section>
  <div class="container">
    <div class="searchWrapper">
      <Logo />
      <button class="custom_btn">RANDOM</button>
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
    grid-template-rows: 5vw auto;
  }
  .contentWrapper {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .searchWrapper {
    width: 90vw;
    display: flex;
    align-items: flex-end;
    margin-bottom: 5px;
    justify-content: space-between;
  }
</style>
