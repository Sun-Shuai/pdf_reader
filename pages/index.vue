<template>
  <div id="app">

    <div id="pdf">
      <pdf/>
    </div>

    <div id="ad">广告位</div>

  </div>
</template>

<script>
  import pdf from '~/components/pdf.vue'

  export default {
    components: {
      pdf
    },
    metaInfo: {},
    data() {
      return {}
    }
  }
</script>

<style>

  #pdf {
    width: 80%;
    background: #70DB55;
  }

  #ad {
    width: 2%;
    background: orange;
  }

</style>
