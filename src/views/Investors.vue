<template>
  <div class="page-investors">
      <div class="top-section">
          
            <menus :extraHeader="true" :title="title" :content="content" :logoColor="'dark'"  />
         
          <!---->
        </div>


    <section class="board-directors">
        <div class="row">
          <div class="columns large-4 large-push-4">
            <div class="intro block">
              <h2 class="title">Our Team Members</h2>
              <p class="content">
                Emergency Need solution has been developed by Team Coconut in a Pilot Hack-a-thon of CTO Forum Bangladesh Innovation Center. Team worked for Emergency Needs to ideate solutions and form audacious ideas to the company’s most pressing business challenges.
              </p>
            </div>
          </div>

          <div class="columns large-4 large-pull-4">
             <!--Block one-->
          </div>

          <div class="columns large-4">
            <!--Block two-->
          </div>
        </div>

        <div class="row">
          <div class="columns large-4">
            <div class="three block" style="background: #fff">
              <h3 class="title">Tanvir Ahmed</h3>
              <p class="content">Team Member</p>
            </div>
          </div>

          <div class="columns large-4">
            <div class="four block" style="background: #fff">
              <h3 class="title">Fahimul Haqoe Jason</h3>
              <p class="content">Team Leader</p>
            </div>
          </div>

          <div class="columns large-4">
            <div class="five block" style="background: #fff">
              <h3 class="title">Shariar Hossain</h3>
              <p class="content">Team Member</p>
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
  name: 'investors',
  data(){
    return{
      title:"Developed by Team Coconut",
      content:"Team Coconut was is a team of CloudCamp Bangladesh. It has formed by inspiration of Mahdee Sir."
    }
  },
  components: {
    footers: footers,
    menus: menu
  },
}
</script>

