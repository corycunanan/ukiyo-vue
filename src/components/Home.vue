<template>
  <div class="Home">
    <!-- Hero -->
    <section class="hero is-large">
      <div class="hero-body">
        <div class="container">
        </div>
      </div>
      <div class="hero-foot">
            <div class="hero-footer-content has-text-centered">
              <p class="hero-footer-text has-text-white has-text-weight-bold is-size-5">Content management made easy, applications made beautiful.</p>
              <a class="button hero-footer-button is-rounded has-text-weight-bold">Let's Talk</a>
            </div>
      </div>
    </section>
    <!-- /Hero -->

    <!-- Who We Are -->
    <section class="is-large has-text-centered">
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
    <section>
      Float
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

.hero
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
  .hero-footer-content
    margin: 0.5em
    .hero-footer-text
      padding-top: calc(0.375em - 1px)
      display: inline-block
      padding-left: 2em
      padding-right: 2em
    .hero-footer-button
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
</style>
