<template>
  <div id="app">
    <div id="nav">
      
    </div>
    <router-view/>
  </div>
</template>
<script>
export default {
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
<style lang="scss">
*{
    margin:0;
    padding:0;
}
</style>
