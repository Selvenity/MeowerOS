<script>
  import Desktop from "./lib/Desktop.svelte";
  import Taskbar from "./lib/Taskbar.svelte";
</script>

<div class="main">
  <Desktop />
  <Taskbar />
</div>

<style>
  .main {
    height: 100vh;
    width: 100vw;
    background-image: url("./assets/meowtain.png");
    background-attachment: fixed;
    background-repeat: no-repeat;
    background-size: cover;
    background-position-y: bottom;
  }
</style>

