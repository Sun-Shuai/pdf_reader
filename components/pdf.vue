<template>
    <div id="app">
      <iframe id="pdf" src="pdf_js/viewer.html"></iframe>
    </div>

</template>

<script>
    export default {
        name: "pdf"
    }
</script>

<style>

  #app{
    height: 100%;
  }

  #pdf{
    width: 100%;
    height: 100%;
  }

</style>
