<script lang="ts">
    let lightTheme = false;
    let switchTheme = (e) => {
        document.documentElement.setAttribute("light-theme", String(!lightTheme));
        lightTheme = !lightTheme;
    }
</script>

<div class="theme-switcher">
    {#if lightTheme === true}
        <img src="../../static/sun.svg" alt="light" style="color: #3D6E8EFF" on:click={switchTheme}>
    {:else}
        <img src="../../static/moon.svg" alt="dark" on:click={switchTheme}>
    {/if}
</div>

<style lang="scss">
  .theme-switcher {
    text-align: right;
    padding: 3rem 3rem;

    img {
      max-width: 35px;
      filter: invert(37%) sepia(46%) saturate(507%) hue-rotate(160deg) brightness(94%) contrast(88%);
      cursor: pointer;
    }
  }
</style>