<div class="pages__contact">
    <h1 class="pages__contact-heading" data-aos="fade-right" data-aos-duration="1200">Contact me!</h1>
    <div class="details" data-aos="fade-right" data-aos-duration="1500">
        <span class="social"><a href="https://github.com/tejasag">Github</a></span>
        <span class="social"><a href="https://discord.com/users/771687332734173185">Discord</a></span>
        <span class="social"><a href="https://twitter.com/AgTejas">Twitter</a></span>
        <span class="social"><a href="mailto:tejas.agarwal.bly@gmail.com">E-Mail</a></span>
    </div>
</div>

<style lang="scss">
  .pages__contact {
    position: relative;
    padding-bottom: 10vh;
  }

  .pages__contact-heading {
    padding-top: 15vh;
    color: var(--landing-page-name-color);
    font-size: 4em;
    font-weight: bold;
    padding-left: 15vw;
    padding-bottom: 0;
  }

  .details {
    display: flex;
    padding-left: 15vw;

    & > .social {
      font-size: 2em;
      padding-top: 3vw;
      padding-right: 2vw;

      & > a {
        color: var(--landing-page-navbar);
      }
    }
  }
</style>