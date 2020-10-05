<template>
  <div class="layout">
    <header>

      <b-navbar class="is-spaced is-fixed-top" :shadow="true" :transparent="true" >

        <template slot="brand">

          <b-navbar-item tag="router-link" :to="{ path: '/' }">
            <g-image src="~/assets/logo.svg" class="logo"></g-image>
          </b-navbar-item>
        </template>

        <template slot="start">
        <div class="navbar-start">
          <strong>
            <b-navbar-item href="/" class="is-primary">HOME</b-navbar-item>
          </strong>
          <strong>
            <b-navbar-item href="/service/">SERVICES</b-navbar-item>
          </strong>
          <strong>
            <b-navbar-dropdown label="OUR WORK">
              <b-navbar-item href="#">
                <strong>About</strong>
              </b-navbar-item>
              <b-navbar-item href="#">
                <strong>Contact</strong>
              </b-navbar-item>
            </b-navbar-dropdown>
          </strong>
          <strong>
            <b-navbar-dropdown label="ABOUT US">
              <b-navbar-item href="/about/">
                <strong>About</strong>
              </b-navbar-item>
              <b-navbar-item href="#">
                <strong>Contact</strong>
              </b-navbar-item>
            </b-navbar-dropdown>
          </strong>
          <strong>
            <b-navbar-item href="#">BLOGS</b-navbar-item>
          </strong>
          </div>
        </template>
        <template slot="end">
          <b-navbar-item >
            <b-button class="button btn">
              <strong >CONTACT US</strong>
            </b-button>
          </b-navbar-item>
        </template>
      </b-navbar>

    </header>
    <slot />
    <footer class="footer has-background-primary">
      <div class="has-text-centered has-text-white">
        <div class="columns">
          <div class="column">
            <g-image src="~/assets/logo-footer.svg" height="38px" width="265px"></g-image>
            <div class="is-spaced">
              <g-image class="pr-3" src="~/assets/twitter.svg" height="40px" width="40px"></g-image>
              <g-image class="pr-3" src="~/assets/instagram.svg" height="40px" width="40px"></g-image>
              <g-image class="pr-3" src="~/assets/facebook.svg" height="40px" width="40px"></g-image>
              <g-image class="pr-3" src="~/assets/youtube.svg" height="40px" width="40px"></g-image>
            </div>
          </div>
          <div class="column">
            <ul>
              <li class="licontent">
                <g-link class="licontentclr" to="/">
                  <strong>COMPANY</strong>
                </g-link>
              </li>
              <br />
              <li class="licontent">
                <g-link class="licontentclr" to="/">
                  <strong>ABOUT US</strong>
                </g-link>
              </li>
              <br />
              <li class="licontent">
                <g-link class="licontentclr" to="/">
                  <strong>OUR WORK</strong>
                </g-link>
              </li>
              <br />
            </ul>
          </div>

          <div class="column">
            <ul>
              <li class="licontent">
                <g-link class="licontentclr" to="/">
                  <strong>SERVICES</strong>
                </g-link>
              </li>
              <br />
              <li class="licontent">
                <g-link class="licontentclr" to="/">
                  <strong>BLOGS</strong>
                </g-link>
              </li>
              <br />
              <li class="licontent">
                <g-link class="licontentclr" to="/">
                  <strong>CAREERS</strong>
                </g-link>
              </li>
              <br />
            </ul>
          </div>
          <div class="column">
            <ul>
              <li class="licontent">
                <g-link class="licontentclr" to="/">
                  <strong>CONTACT US</strong>
                </g-link>
              </li>
              <br />
              <br />
              <li class="licontent">
                © Reveation Labs
                <br />All Rights Reserved
              </li>
            </ul>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>


<style lang="scss">

@import "~bulma/sass/utilities/_all";
$primary: #2444eb;
$primary-invert: findColorInvert($primary);
$twitter: #4099ff;
$twitter-invert: findColorInvert($twitter);

// Setup $colors to use as bulma classes (e.g. 'is-twitter')
$colors: (
  "white": (
    $white,
    $black
  ),
  "black": (
    $black,
    $white
  ),
  "light": (
    $light,
    $light-invert
  ),
  "dark": (
    $dark,
    $dark-invert
  ),
  "primary": (
    $primary,
    $primary-invert
  ),
  "info": (
    $info,
    $info-invert
  ),
  "success": (
    $success,
    $success-invert
  ),
  "warning": (
    $warning,
    $warning-invert
  ),
  "danger": (
    $danger,
    $danger-invert
  ),
  "twitter": (
    $twitter,
    $twitter-invert
  )
);

// Links
$link: $primary;
$link-invert: $primary-invert;
$link-focus-border: $primary;


// Import Bulma and Buefy styles
@import "~bulma";
@import "~buefy/src/scss/buefy";
</style>

<style>
@media screen and (max-width: 600px) {
.logo{
width:195px;
height:28px;
}

}
.navbar-start{
  flex-grow: 1;
  justify-content: center;
}



body {
 font-family: 'Rubik';
  margin: 0;
  padding: 0;
  line-height: 1.5;
}


.btn {
  border-color: #2444eb;
  color:#2444eb;
  background-color: transparent;
  border-radius: 6px;
}
.layout {
  width: 100%;
  margin: auto;
  padding-left: 0px;
}
.content {
  margin-left: 70px;
  margin-top: 10px;
  color: white;
  list-style-type: none;
}
.licontent {
  color: white;
  list-style-type: none;
}
.licontentclr {
  color: white;
}
</style>
