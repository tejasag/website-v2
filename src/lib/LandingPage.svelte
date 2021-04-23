<script lang="ts">
    import Navbar from "$lib/Navbar.svelte";
    import ThemeSwitcher from "$lib/ThemeSwitcher.svelte"
</script>

<div class="pages__landing">
    <ThemeSwitcher/>
    <div class="landing-content">
        <h1 class="heading">Hey there!<br/> I'm
            <span class="landing-page__name">Tejas Agarwal</span>
        </h1>
        <Navbar/>
    </div>
</div>

<style lang="scss">
  .pages__landing {
    height: 100vh;
    position: relative;
  }

  .landing-content {
    position: absolute;
    top: 30%;
    padding: 1vh 20vw;
    background-position-x: 20vw;

    .landing-page__name {
      color: var(--landing-page-name-color);
    }

    h1 {
      font-size: 4em;
      color: var(--landing-page-header-color);
      animation: fade ease 0.75s;
      animation-delay: 1.1s;
      transition: color 1s;
    }
  }

  @keyframes fade {
    0% {
      opacity: 0;
    }
    50% {
      opacity: 0.5;
    }
    100% {
      opacity: 1;
    }
  }

  @media screen and (max-width: 600px) {
    .landing-content {
      padding-left: 15vw;
      padding-top: 0.25vh;

      h1 {
        font-size: 3em;

      }
    }
  }
</style>
