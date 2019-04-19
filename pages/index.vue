<template>
  <div id="app">

    <iframe src="/pdf_js/viewer.html" style="width: 100%;height: 100%"></iframe>

  </div>
</template>

<script>

  export default {
    components: {},
    metaInfo: {},
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
    margin: 0 auto;
    height: 100%;
    width: 100%;
    position: fixed;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    background: #7f828b;
  }
</style>
