<svelte:head>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.11.0/devicon.min.css">
</svelte:head>

<div class="pages__about">
    <div class="content">
        <div class="header-container">
            <h1 class="header">about me</h1>
        </div>
        <div class="details-container" data-aos="fade-up" data-aos-duration="1500">
            <h2 class="details">hi! i am tejas agarwal. i'm a high school student and tech enthusiast! i started
                programming in early 2020 and some of my favorite programming languages include rust, typescript &
                golang. besides programming, you can find me playing lawn tennis, doing 3d art, watching anime or just
                hanging out at Hack
                Club's slack
                <br/> <br/>
                check out my <a href="https://github.com/tejasag">github</a> for my projects and some pretty random
                things i make for some reason. look at my weird tweets @ <a
                        href="https://twitter.com/AgTejas">AgTejas</a> or shoot me an <a
                        href="mailto:tejas.agarwal.bly@gmail.com">email</a>
            </h2>
        </div>
    </div>
</div>

<style lang="scss">
  .pages__about {
    position: relative;
    padding: 4rem 10rem 3rem;
  }

  .content {

    > .header-container {
      margin: 4rem 4rem 1rem 5rem;
      padding-bottom: 0.001rem;

      > .header {
        font-size: 3em;
        color: var(--landing-page-name-color);
        font-weight: bold;
        position: absolute;
        transition: all 1s;
      }
    }

    > .details-container > .details {
      margin: 5rem 6rem 6rem 5rem;
      color: var(--landing-page-header-color);
      font-size: 1.25em;
      font-weight: lighter;
      transition: color 0.5s, margin-top 1.2s, max-width 0.7s, font-size 0.7s;
      color: #9a9999;
      max-width: 75vw;

      a {
        color: var(--landing-page-navbar);
      }
    }

    &:hover {
      > .header-container {
        > .header {
          transform: translateX(-2em) rotateZ(-90deg) translateY(-2em) translateX(-60%);
          transition: transform 1s;
        }
      }

      > .details-container > .details {
        margin-top: 3rem;
        font-size: 1.5rem;
        color: var(--about-page-details);
        max-width: 50vw;

        transition: color 0.5s, margin-top 1.2s, max-width 0.7s, font-size 0.7s;
      }
    }
  }

  @media screen and (max-width: 600px) {
  }
</style>
