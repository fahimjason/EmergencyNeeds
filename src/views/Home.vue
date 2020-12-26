

<template>
  <div class="home">
   
      <menus class="site-header" showTitle="true" />
    
  <section class="home-about">
    <div class="row column large-9 xlarge-6 xxlarge-4">
      <h2 class="section-title">How Does This Work?</h2>
      <p class="content">
        In today’s fast paced world, you’ve got places you need to be and want to get everything quickly and near. Wouldn’t it be nice if there were a service platform that changed the way you get around daily? Introducing Emergency Needs, an innovative service plat form that helps people get to their Needs faster and hassle-free. Getting started is as easy as tapping a button in our app.
      </p>
    </div>

    <div class="row medium-up-2 large-up-4">
      <div class="column">
        <div class="home-about-block">
          <h3 class="title icon-download">Download The App</h3>
          <p class="content">Head over to the app store and download the Emergency Needs app. You’re just a few taps away from getting your needy service.</p>
        </div>
      </div>

      <div class="column">
        <div class="home-about-block">
          <h3 class="title icon-unicorn">Request A Needs</h3>
          <p class="content">We can get you there. Simply request a need on the app and we'll connect you with a unicorn immediately.</p>
        </div>
      </div>

      <div class="column">
        <div class="home-about-block">
          <h3 class="title icon-price">Pick A Price</h3>
          <p class="content">Pick the valuation you're willing to pay and your service is set up. The only surge is the acceleration you get when taking off.</p>
        </div>
      </div>

      <div class="column">
        <div class="home-about-block">
          <h3 class="title icon-success">Need Off To Success!</h3>
          <p class="content">After matching with your service and agreeing to its terms, you’ll be all set. Your service provider will arrive shortly to pick you up.</p>
        </div>
      </div>
    </div>
  </section>

  <section class="home-story">
    <div class="row column large-9 xlarge-6 xxlarge-4">
      <h2 class="section-title">Our Story</h2>
      <p class="content">
        Emergency Needs solution has been developed by Team Coconut in a Pilot Hack-a-thon of CTO Forum Bangladesh Innovation Center. Team worked for Emergency Needs to ideate solutions and form audacious ideas to the company’s most pressing business challenges. At first one of us talked about an app for getting blood emergency. Whether it was modern society’s reliance on science over magic or not, we’ll never know the cause of their Ozymandian downfall and fade to obscurity. Moved by empathy, romance, and free enterprise, they saw an opportunity to marry society’s demand for faster, more flexible service to underutilized beasts of labor through an on-demand market making service app. 
      </p>
    </div>
  </section>

  <section class="home-sign-up">
    <div class="row column">
      <img class="icon-w" src="images/wr-home-W.png">

      <form onsubmit="javascript:void(0);">
        <input type="email" placeholder="Enter your email address">
        <button type="button">Submit</button>
      </form>

      <h2 class="section-title">Sign Up</h2>

      <p class="content">Emergency Needs is coming soon! Enter your email to enter the limited private beta</p>

      <div class="apps">
        <a class="app-icon" href=""><img src="images/wr-home-apple.png"></a>
        <a class="app-icon" href=""><img src="images/wr-home-google.png"></a>
        <a class="app-icon" href=""><img src="images/wr-home-blackberry.png"></a>
        <a class="app-icon" href=""><img src="images/wr-home-Xiaomi.png"></a>
      </div>

      <div class="social">
        <a class="icon-fb" href="">Facebook</a>
        <a class="icon-tw" href="">Twitter</a>
        <a class="icon-ig" href="">Instagram</a>
        <a class="icon-wc" href="">Wechat</a>
        <a class="icon-wb" href="">Weibo</a>
      </div>
    </div>
  </section>

  <section class="home-quote">
    <div class="row column medium-8 xxlarge-6">
      <div class="quote-wrap">
        <div class="quote">
          “It's really an amazing app for getting all of service in a platform. And here you won't to pay for the important services.”
        </div>
        <div class="quoter">- Satisfied Emergency Needs user</div>
      </div>
    </div>
  </section>

  <section class="kraken-callout">
    <div class="row">
      <div class="columns medium-6 xxlarge-4 xxlarge-offset-2">
        <img src="images/wr-home-kraken.png">
      </div>

      <div class="columns medium-6 xlarge-5 xxlarge-4">
        <h4 class="title">Coming Soon</h4>
        <p class="content">
          We’re looking to provide you all kinds of service from educational, cultural, and to all othres services.
        </p>
      </div>
    </div>
  </section>


    <footers />
  </div>
</template>

<script>
// @ is an alias to /src
import footers from '@/components/footer.vue'
import menu from '@/components/menu.vue'

export default {
  name: 'home',
  components: {
    footers: footers,
    menus: menu
  },
}

</script>
