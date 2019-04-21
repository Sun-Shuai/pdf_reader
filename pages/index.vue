<template>
  <div id="app">

    <iframe id="pdf" src="pdfjs/web/viewer.html" frameborder="0"></iframe>


    <!--<div style="z-index:999;display: block; position: fixed; left: 10px; top: 300px;">-->

      <!--<a href="#">-->
        <!--<img width="320" height="300"-->
             <!--src="qrcode.png">-->
      <!--</a>-->

    <!--</div>-->

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

  html, body {
    height: 100%;
    width: 100%;
  }

  #app {
    height: 100%;
    width: 100%;
    position: fixed;
    padding: 0
  }

  #pdf {
    width: 100%;
    height: 100%;
  }


</style>
