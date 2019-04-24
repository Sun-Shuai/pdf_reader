<template>
  <div id="app">

    <iframe id="pdf" src="pdfjs/web/viewer.html" frameborder="0"></iframe>


    <div style="z-index:999; position:absolute; right: 20px; bottom: 20px;">

      <div style="height: 200px;width: 240px">
        <el-carousel height="200px">
          <el-carousel-item v-for="item in pics" :key="item.url">
            <a href="#">
              <img :width="240" :height="200" :src="item.url"/>
            </a>
          </el-carousel-item>
        </el-carousel>
      </div>

    </div>

  </div>


</template>

<script>

  import 'element-ui/lib/theme-chalk/index.css'

  export default {
    components: {},
    data() {
      return {
        pics: [
          {url: require("../static/qrcode.png")},
          // {url: require("../static/qrcode.png")},
          // {url: require("../static/qrcode.png")}
        ]
      }
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
