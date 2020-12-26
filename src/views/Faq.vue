<template>
<div class="page-faq">

    <menus class="site-header" :extraHeader="true" :title="title"  />

  <section class="faq-list">
    <div class="row column medium-10 large-8 xxlarge-6">
      <dl>
        <dt>Q: Why should I use this app?</dt>
        <dd>A: Emergency Needs is a faster, safer, and more reliable platform. You will get here any emergency needs such as Blood donor, Health service, Legal service and many others services.</dd>
        <dt>Q: How do I request for an Emergency Needs?</dt>
        <dd>A: Simply download our app, then tap a button to begin. Your srevice provider will reach to you shortly.</dd>
        <dt>Q: How much does it cost?</dt>
        <dd>A: We have two kinds of service free and premium. You will get the most important service freely such as Blood donor, Health service, Fire Service, Legal service(from Police) ect. And some of our services are premium such Law service from a lawyer, Electrical service etc. You will set the maximum price you’re willing to pay for a given need and then then Emergency Needs matches you with a service provider who willing to accept your price.</dd>
        <dt>Q: How does it work?</dt>
        <dd>A: Our service is powered by a complex algorithm which efficiently matches idle service providers with needs based on factors such as proximity and shortest time-to-destination. The system is built on a serverless architecture, which makes running and scaling our backend services simple and cost-effective, allowing us to reliably serve the needs of Emergency Needs ever growing user base.</dd>
        <dt>Q: What if I have a complaint about my service?</dt>
        <dd>A: Emergency Needs is a customer obsessed company. We value each customer and want to ensure a positive experience. Therefore, we’ve staffed our customer service team with serverless chatbots that are available 24/7 to assist you.</dd>
        <dt>Q: How do I cancel my need?</dt>
        <dd>A: Tap the “Cancel Need” button in the Emergency Needs app.</dd>
        <dt>Q: Can I use Emergency Needs internationally?</dt>
        <dd>A: Hope, you will able to use Emergency Needs internationally in future.</dd>
        <dt>Q: How do I pay for my service?</dt>
        <dd>A: After creating a Emergency Needs account, fill in your payment method such as credit card, debit card, or mobile banking. After completing your service, you will automatically be charged the fees.</dd>
        <dt>Q: Why do you charge a service fee?</dt>
        <dd>A: The service fee is a fixed charge added to every premium service. This helps us pay for our on-going maintenance and operating costs required to run the service and tend to our service providers.</dd>
      </dl>
    </div>
  </section>
  <footers />
</div>

</template>

<script>
import footers from '@/components/footer.vue'
import menu from '@/components/menu.vue'

export default {
  name: 'faq',
  data(){
    return{
      title:"Frequently Asked Questions",
          }
  },
  components: {
    footers: footers,
    menus: menu
  },
}
</script>

