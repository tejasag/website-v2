<script lang="ts">
    import Navbar from "$lib/Navbar.svelte";
    import ThemeSwitcher from "$lib/ThemeSwitcher.svelte"
</script>

<div class="pages__landing">
    <ThemeSwitcher/>
    <div class="landing-content">
        <h1 class="heading" data-aos="fade-right" data-aos-duration="1200">hey there!<br/> i'm
            <span class="landing-page__name">tejas agarwal</span>
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
    padding: 1rem 20rem;
    background-position-x: 20rem;

    .landing-page__name {
      color: var(--landing-page-name-color);
    }

    h1 {
      font-size: 4em;
      color: var(--landing-page-header-color);
      transition: color 1s;
      animation: rotateHeader;
    }
  }

  @media screen and (max-width: 600px) {
    .landing-content {
      padding-left: 15rem;
      padding-top: 0.25rem;
      top: 20%;

      h1 {
        font-size: 3em;
      }
    }
  }
</style>
