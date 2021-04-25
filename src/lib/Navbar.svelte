<script lang="ts">
    const gotoAbout = (e) => {
        document.querySelector(".pages__about").scrollIntoView({
            behavior: "smooth",
            block: "start",
            inline: "nearest"
        })
    }
</script>

<nav>
    <ul class="navbar">
        <li class="navbar__component"><a href="#about" on:click={gotoAbout}>/about</a></li>
        <li class="navbar__component"><a href="/projects">/projects</a></li>
        <li class="navbar__component"><a href="/hackathons">/hackathons</a></li>
        <li class="navbar__component"><a href="/contact">/contact</a></li>
    </ul>
</nav>

<style lang="scss">
  .navbar {
    list-style: none;
    padding-left: 0;
    margin: 0;
    display: block;
    font-size: 1em;


    li {
      display: inline-block;
      font-size: 1.5em;
      padding-top: .5em;
      font-weight: 400;
      color: white;

      &:nth-child(1) {
        animation: fade ease .6s;
        opacity: 0;
        animation-fill-mode: forwards;
        animation-delay: 1.3s;
      }

      &:nth-child(2) {
        animation: fade ease .6s;
        opacity: 0;
        animation-fill-mode: forwards;
        animation-delay: 1.4s;
      }

      &:nth-child(3) {
        animation: fade ease .6s;
        opacity: 0;
        animation-fill-mode: forwards;
        animation-delay: 1.5s;
      }

      &:nth-child(4) {
        animation: fade ease .6s;
        opacity: 0;
        animation-fill-mode: forwards;
        animation-delay: 1.6s;
      }

      a {
        padding-right: 0.5em;
        color: var(--landing-page-navbar);
        transition: color 1.25s;
      }
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
</style>