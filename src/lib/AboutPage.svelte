<div class="pages__about">
    <div class="content">
        <h1 class="header" data-aos="fade-right" data-aos-duration="1200">
            About me
        </h1>
        <h2 class="details" data-aos="fade-right" data-aos-duration="1500">
            Hi! I am Tejas Agarwal, a full stack web developer from India! <br/> I have been developing for about a year now
            and some of my favourite languages include TypeScript and Rust!<br/><br/>When I am not developing, I play Lawn Tennis, make
            3D art or hang around at <a href="/hackclub">HackClub's slack</a>
        </h2>
    </div>
</div>

<style lang="scss">
  .pages__about {
    height: 100vh;
    max-height: 100vh;
    position: relative;
  }

  .header {
    padding-left: 15vw;
    padding-top: 20vh;
    padding-bottom: 0;
    font-size: 4em;
    color: var(--landing-page-name-color);
    font-weight: bold;
  }

  .details {
    padding-left: 15vw;
    padding-right: 10vw;
    padding-top: 5vh;
    color: var(--landing-page-header-color);
    font-size: 1.5em;
    font-weight: lighter;

    a {
      color: var(--landing-page-navbar);
    }
  }

  @media screen and (max-width: 600px) {
    .content {
      padding-left: 10vw;
    }

    .header {
      font-size: 3em;
      padding-left: 0;
      padding-top: 10vh;
    }

    .details {
      padding-left: 0;
    }
  }
</style>
