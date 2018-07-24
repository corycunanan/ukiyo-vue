<template>
  <div class="Home">
    <!-- Hero -->
    <section class="hero hero-clouds-background">
      <div class="hero-body hero-body-extra-padding">
          <figure class="image hero-logo">
            <img src="./../assets/logos/ukiyo-logo-2-circle.png">
          </figure>
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
    <section class="has-text-centered about-us-section">
      <div class="flex-container about-us-section-content">
        <div class="has-text-left about-us-section-content-column text-card">
          <p class="text-card-text">
            Ukiyo is a San Fernando Valley based company founded in the summer of 2018 by brothers Kevin and
             Cory Cunanan. Ukiyo strives to create affordable and elegant digital solutions for local businesses.
          </p>
          <a class="button text-card-button is-rounded has-text-weight-bold">Learn More About Us</a>

        </div>
        <div class="card about-us-section-content-column profile-card">
          <div class="profile-card-content">
            <figure class="image card-image">
              <img src="./../assets/images/Headshots/kevin.jpg" class="circle-picture">
            </figure>
            <h1 class="card-title">Kevin Cunanan</h1>
            <h1 class="card-subtitle">Chief Engineer</h1>
          </div>
        </div>
        <div class="card about-us-section-content-column profile-card">
          <div class="profile-card-content">
            <figure class="image card-image">
              <img src="./../assets/images/Headshots/cory.jpg" class="circle-picture">
            </figure>
            <h1 class="card-title">Kevin Cunanan</h1>
            <h1 class="card-subtitle">Lead Designer</h1>
          </div>
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
            <p class="float-section-content-column-text">An affordable content management system with a user-friendly interface for creating and managing APIs.</p>
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
    <section class="portfolio-section">
      <div class="portfolio-section-content">
        <div class="portfolio-section-content-images has-text-centered background-is-red">
          Pictures
        </div>
        <div class="portfolio-section-content-text">
          <h1 class="portfolio-section-content-text-title color-is-black has-text-weight-bold">We like to show off. </h1>
          <h2 class="portfolio-section-content-text-subtitle">View our latest projects and the mindset behind them.</h2>
          <p class="portfolio-section-content-text-paragraph">At Ukiyo, we specialize in creative and elegant designs to optimize your digital presence, while also providing you the tools to manage your own content and data on the fly. </p>
          <a class="">View our full portfolio</a>
        </div>
      </div>
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
.hero-body-extra-padding
  padding: 20em
  .hero-logo
    width: 25%
    position: absolute
    left: 50%
    margin-left: -10em
    top: 50%
    margin-top: -10em
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

.about-us-section
  padding: 4em 0 4em 0
  .about-us-section-content
    display: flex
    justify-content: center
    .about-us-section-content-column
      width: 25%
      margin: 2em
    .text-card
      flex-wrap: wrap
      padding: 0 2em 0 2em
      .text-card-text
        font-size: 1.25em
        line-height: 1.75em
        margin-bottom: 1.5em
      .text-card-button
        background-color: #3CBECC
        border-color: transparent
        color: white
        width: 100%
        padding-top: 1.25em
        padding-bottom: 1.25em
        box-shadow: 0 2px 8px 0 rgba(0, 0, 0, 0.2)

    .profile-card
      width: 21%
      height: 20em
      background: url('../assets/images/dan-aragon-382945-unsplash-black.jpg')
      background-position: bottom
      outline: 1px solid rgb(83,193,204)
      outline-offset: 5px
      .profile-card-content
        margin-top: 2.5em
        margin-bottom: 2em
        .card-image
          margin-bottom: 1em
          width: 150px
          height: 150px
          display: inline-block
          .circle-picture
            border-radius: 50%
        .card-title
          color: white
          font-weight: bold
          font-size: 1.15em
        .card-subtitle
          color: white

.float-section
  background: url(../assets/images/chuttersnap-255211-unsplash-blue.jpg) center / cover
  color: white
  .float-section-title
    background: rgba(103,0,0,.38)
    color: white
    .flex-container
      display: flex
      margin: 1.25em 0 1.25em 0
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

.portfolio-section
  .portfolio-section-content
    display: flex
    justify-content: center
    align-items: center
    .portfolio-section-content-images
      width: 25%
      height: 100%
    .portfolio-section-content-text
      padding-left: 6em
      width: 60%
      justify-content: left
      .portfolio-section-content-text-title
        font-size: 4em
      .portfolio-section-content-text-subtitle
      .portfolio-section-content-text-paragraph
      .portfolio-section-content-text-button

.button
.button-blue
  background-color: #3CBECC
.button-red
  background-color: #993333
.button-shadow
  box-shadow: 0 2px 8px 0 rgba(0, 0, 0, 0.2)

.background-is-blue
  background-color: #3CBECC
.color-is-blue
  color: #3CBECC
.background-is-black
  background-color: rgb(0,0,0)
.color-is-black
  color: rgb(0,0,0)
.background-is-red
  background-color: rgb(153,51,51)
.color-is-red
  color: rgb(153,51,51)
</style>
