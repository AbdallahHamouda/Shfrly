<template>
  <div class="home">
    <navy />
    <hero />
    <gallery />
    <homeemail />
    <about />
    <foot />
  </div>
</template>

<script>
// @ is an alias to /src
import navy from '@/components/nav.vue'
import hero from '@/components/zero.vue'
import gallery from '@/components/gallery.vue'
import homeemail from '@/components/homeemail.vue'
import about from '@/components/about.vue'
import foot from '@/components/footer.vue'

export default {
  name: 'Home',
  components: {
    navy,
    hero,
    gallery,
    homeemail,
    about,
    foot
},
metaInfo: {
      // if no subcomponents specify a metaInfo.title, this title will be used
      title: 'Logo_art99',
      // all titles will be injected into this template
      titleTemplate: '%s | Logo and graphic designer Freelancer',
    meta: [{
      vmid: 'description',
      name: 'description',
      content: 'Graphics designer and logo makerFreelancer  ready to join any team.DM 📥 us to get the best customized design at best rates.PayPal accepted..',
  },
  {
    vmid: 'keywords',
    name: 'keywords',
    content:'freelancer,logo,logodesigner,designer,graphic,design,free,art'
  }]
    }
}
</script>
