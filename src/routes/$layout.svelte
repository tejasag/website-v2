<slot/>

<style lang="scss" global>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,300;0,400;0,600;0,700;1,200;1,300;1,500;1,900&display=swap');

  :root {
    --bg-color: #26262d;
    --landing-page-header-color: white;
    --landing-page-navbar: #acf1c9;
    --landing-page-name-color: #d56e6e;
  }

  html[light-theme="true"] {
    --bg-color: #eedbc4;
    --landing-page-header-color: #3d6e8e;
    --landing-page-navbar: #707f74;
  }

  * {
    padding: 0;
    margin: 0;
    font-family: 'Poppins', sans-serif;
  }

  body {
    transition: background-color 0.30s;
    max-width: 100vw;
    min-height: 100vh;
    position: relative;
    background-color: var(--bg-color);
  }

  body::before {
    background-image: url(background.png);
    background-repeat: repeat;
    background-size: 63px;
    content: "";
    position: absolute;
    top: 0px;
    right: 0px;
    left: 0px;
    bottom: 0px;
    opacity: 0.60;
  }
</style>