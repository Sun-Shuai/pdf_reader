<template>
  <div id="app">

    <iframe id="pdf" src="pdf_js/viewer.html"></iframe>

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
