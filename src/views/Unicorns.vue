<template>
<div class="page-unicorns">
    
    <menus class="site-header" :extraHeader="true" :title="title" :logoColor="'dark'"  />

 <div class="row column medium-10 large-8 xxlarge-6" style="background: #000; color: #fff;">
    <p class="content">
      Emergency Needs is an excellent platform for getting different service in a platform. Here you will get any kind of emergncy service at any time.
    </p>
    <p class="content">
      But all of our services aren't free. Some of our services are free and some are premium.
    </p>
    <p class="content">Please see below about that...</p>
  </div>

  <section class="unicorns-list">

    <div class="row">
      <div class="unicorn jimmy">
        <div class="columns medium-5 large-6 xlarge-5 xlarge-offset-1">
          <img src="images/wr-unicorn-one.png" alt="Jimmy Three Legs">
        </div>

        <div class="columns medium-7 large-6 xlarge-5 xxlarge-4">
          <h2 class="title">Free Services</h2>
          <div class="subtitle">Most imprtant Needs</div>
          <p class="content">
            You will get the most important service freely such as Blood donor, Health service, Fire Service, Legal service(from Police) ect.  
          </p>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="unicorn henry">
        <div class="columns medium-5 medium-push-7 large-6 large-push-6 xlarge-5 xlarge-offset-1 xlarge-push-5">
          <img src="images/wr-unicorn-two.png" alt="Hot Shoe Henry">
        </div>

        <div class="columns medium-7 medium-pull-5 large-6 large-pull-6 xlarge-5 xlarge-pull-5 xxlarge-4 xxlarge-offset-1">
          <h2 class="title">Premium Services</h2>
          <div class="subtitle">General Services</div>
          <p class="content">
            Some of our services are premium such Law service from a lawyer, Electrical service etc. You will set the maximum price you’re willing to pay for a given need and then then Emergency Needs matches you with a service provider who willing to accept your price.
          </p>
        </div>
      </div>
    </div>

    
  </section>
  <footers />
</div>

</template>

<script>
import footers from '@/components/footer.vue'
import menu from '@/components/menu.vue'

export default {
  name: 'unicorns',
  data(){
    return{
      title:"About Emergency Needs",
      content:"The app is what makes this service exist, but the service provider make it move. Meet them and see who you are servicing with!"
    }
  },
  components: {
    footers: footers,
    menus: menu
  },
}
</script>

