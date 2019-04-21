<template>
  <div id="app" style="padding: 0">

    <iframe id="pdf" src="pdfjs/web/viewer.html" frameborder="0"></iframe>

  </div>
</template>

<script>

  export default {
    components: {},
    data() {
      return {}
    }
  }
</script>

<style>

  html,body{
    height: 100%;
    width: 100%;
  }

  #app {
    height: 100%;
    width: 100%;
    position: fixed;
  }

  #pdf {
    width: 100%;
    height: 100%;
  }


</style>
