<template>
  <div id="app">
    <!-- Navbar -->
    <nav class="navbar" id="navbar">
      <!-- Nav logo -->
      <div class="navbar-brand">
        <a class="navbar-item">
          <img src="./assets/logos/ukiyo-logo-2.png">
        </a>
      </div>
      <!-- /Nav logo -->
      <!-- Nav menu -->
      <div class="navbar-end navbar-menu has-text-weight-light">
        <router-link to="/" class="navbar-item r-item">Home</router-link>
        <router-link to="about" class="navbar-item r-item">About Us</router-link>
        <router-link to="float" class="navbar-item r-item">Float</router-link>
        <router-link to="portfolio" class="navbar-item r-item">Our Works</router-link>
      </div>
      <div class="navbar-item">
        <p class="control">
          <a class="button navbar-button is-rounded has-text-white">
            <span>Contact Us</span>
          </a>
        </p>
      </div>
      <!-- Nav menu -->
    </nav>
    <!-- Navbar -->
    <router-view></router-view>
    <!-- Footer -->
    <footer class="footer">
      <div class="footer-content">
        <div class="footer-brand footer-section">
          <div class="footer-item">
            <p>©2018</p>
          </div>
          <div class="footer-item footer-logo">
            <img src="./assets/logos/ukiyo-logo-2.png">
          </div>
        </div>
        <div class="footer-links footer-section">
          <div class="footer-item">
            <p>Visit Our Blog</p>
          </div>
          <div class="footer-item">
            <p>Sitemap</p>
          </div>
          <div class="footer-item">
            <p>Get a Free Mockup</p>
          </div>
        </div>
        <div class="footer-icons footer-section">
          <div class="footer-item">
            <span class="icon has-text-info">
              <i class="fab fa-instagram"></i>
            </span>
          </div>
        </div>
      </div>
    </footer>
    <!-- /Footer -->
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="sass">
@import '../node_modules/bulma/bulma.sass'
@import '/mq'

.navbar
  padding: 1em
  position: fixed
  width: 100%
  background-color: #1A1A1A
  .navbar-brand
  .navbar-end
    .navbar-item
      color: white
      margin-left: 1em
      margin-right: 1em
      &:hover
        color: white
        background-color: black
        border-radius: 25%
  .navbar-button
    background-color: #993333
    border-color: transparent
    padding-left: 1.5em
    padding-right: 1.5em

.footer
  background-color: #020101
  color: white
  padding-left: 4em
  padding-right: 4em
  padding: 0 4em 0 4em
  .footer-content
    display: flex
    justify-content: center
    align-items: center
    .footer-section
      display: flex
      width: 33%
    .footer-brand
      align-items: center
      .footer-logo
        width: 200px
        padding-left: 6em
    .footer-links
      width: 60%
      justify-content: center
      .footer-item
        padding: 2em
    .footer-icons
      justify-content: flex-end
</style>
