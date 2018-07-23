<template>
  <div class="Home">
    <!-- Hero -->
    <section class="hero is-large hero-clouds-background">
      <div class="hero-body">
        <div class="container">
        </div>
      </div>
      <div class="hero-foot">
            <div class="hero-foot-content has-text-centered">
              <p class="hero-foot-content-text has-text-white has-text-weight-bold is-size-5">Content management made easy, applications made beautiful.</p>
              <a class="button hero-foot-content-button is-rounded has-text-weight-bold">Let's Talk</a>
            </div>
      </div>
    </section>
    <!-- /Hero -->

    <!-- Who We Are -->
    <section class="has-text-centered">
      <div class="flex-container">
        <div class="column has-text-left text-card">
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris.
          </p>
        </div>
        <div class="column card profile-card">
          <figure class="image card-image">
            <img src="./../assets/images/Headshots/kevin.jpg" class="circle-picture">
          </figure>
          <h1 class="card-title">Kevin Cunanan</h1>
          <h1 class="card-subtitle">Kevin Cunanan</h1>
        </div>
        <div class="column card profile-card">
          <figure class="image card-image">
            <img src="./../assets/images/Headshots/kevin.jpg" class="circle-picture">
          </figure>
          <h1 class="card-title">Kevin Cunanan</h1>
          <h1 class="card-subtitle">Kevin Cunanan</h1>
        </div>
      </div>
    </section>
    <!-- /Who We Are -->

    <!-- Float -->
    <section class="hero has-text-centered float-section blue-overlay">
      <div class="float-section-title">
        <div class="flex-container">
          <div class="float-section-title-main-title">
            <span class="float-section-title-main-title-icon">
              <figure class="image is-48x48">
                <img src="./../assets/icons/typicons_2-0-7_feather_301_0_ffffff_none.png">
              </figure>
            </span>
            <h1 class="float-section-title-main-title-text">
              float
            </h1>
          </div>
          <div class="float-section-title-subtitle">
            <h2 class="float-section-title-subtitle-text">
              Make a dynamic website quickly, easily, and affordably.
            </h2>
            <a class="button float-section-title-subtitle-button is-rounded has-text-weight-bold">
              See how it works
            </a>
          </div>
        </div>
      </div>
      <div class="float-section-content">
        <div class="columns float-section-content-columns">
          <div class="column float-section-content-column">
            <span class="icon is-large float-section-content-column-icon">
              <i class="fas fa-3x fa-table"></i>
            </span>
            <p class="float-section-content-column-text">An affordable content management system with a user-friendly interface for creating and managing APIs.</p>
          </div>
          <div class="column float-section-content-column">
            <span class="icon is-large float-section-content-column-icon">
              <i class="fas fa-3x fa-database"></i>
            </span>
            <p class="float-section-content-column-text">Float allows you  to take control of your data while removing the need for developing a backend.</p>
          </div>
          <div class="column float-section-content-column">
            <span class="icon is-large float-section-content-column-icon">
              <i class="fas fa-3x fa-sitemap"></i>
            </span>
            <p class="float-section-content-column-text">Float easily interfaces with our pre-made and customizable mobile-friendly templates.</p>
          </div>
        </div>
      </div>
    </section>
    <!-- /Float -->

    <!-- Portfolio -->
    <section>
      Portfolio
    </section>
    <!-- /Portfolio -->
  </div>
</template>

<script>
export default {
  name: 'home'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="sass" scoped>
@import '../mq'

.hero-clouds-background
  background: url('../assets/images/anton-darius-thesollers-370048-unsplash.jpg') center / cover
  background-position: bottom
  position: relative

.hero-foot
  position: absolute
  bottom: 0
  width: 100%
  height: 15%
  padding: 1em 0
  background-color: rgba(0,0,0,.5)
  .hero-foot-content
    margin: 0.5em
    .hero-foot-content-text
      padding-top: calc(0.375em - 1px)
      display: inline-block
      padding-left: 2em
      padding-right: 2em
    .hero-foot-content-button
      padding-left: 4em
      padding-right: 4em
      padding-top: 1.1em
      padding-bottom: 1.1em
      background-color: #3CBECC
      border-color: transparent
      color: white

.flex-container
  display: flex
  justify-content: center
  .column
  .text-card
    flex-wrap: wrap
  .profile-card
    .card-image
      margin: 2.5em
      width: 150px
      height: 150px
      .circle-picture
        border-radius: 50%

.float-section
  background: url(../assets/images/chuttersnap-255211-unsplash-blue.jpg) center / cover
  color: white

  .float-section-title
    background: rgba(103,0,0,.38)
    color: white
    .flex-container
      display: flex
      .float-section-title-main-title
        margin: 0 0 0 3.5em
        .float-section-title-main-title-icon
          display: inline-block
          margin:  0 2em 0 2em
        .float-section-title-main-title-text
          font-size: 4em
          font-weight: bold
          display: inline-block
      .float-section-title-subtitle
        margin: auto
        .float-section-title-subtitle-text
          display: inline-block
          font-weight: 200
          font-size: 1.5em
          margin-right: 2em
        .float-section-title-subtitle-button
          display: inline-block
          background-color: rgb(60,190,204)
          color: white
          border-color: transparent
      .image
        margin: auto
  .float-section-content
    .float-section-content-columns
      margin: 5em 0 5em 0
      .float-section-content-column
        margin: 0
        padding: 0 7em 0 7em
      .float-section-content-column-icon
        margin-bottom: 2em
      .float-section-content-column-text
        font-size: 1.01em
        line-height: 2em
</style>
