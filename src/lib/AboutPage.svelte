<div class="pages__about">
    <div class="content">
        <h1 class="header" data-aos="fade-right" data-aos-duration="1200">
            About me
        </h1>
    </div>
</div>

<style lang="scss">
  .pages__about {
    height: 100vh;
    position: relative;
  }

  .header {
    padding: 20vh 20vw;
    font-size: 4em;
    color: var(--landing-page-header-color);
    font-weight: bold;
  }

  @media screen and (max-width: 600px) {
    .content {
      padding-left: 15vw;
      padding-top: 0.25vh;

      .header {
        font-size: 3em;
      }
    }
  }
</style>
