<template>
  <div id="app">

    <el-row :gutter="1">

      <el-col :span="3">
        <div id="ad">This is ad area!</div>
      </el-col>


      <el-col :span="18">
        <div id="pdf">
          <pdf/>
        </div>
      </el-col>


      <el-col :span="3">
        <div id="function">This is function area!</div>
      </el-col>

    </el-row>


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

  html, body {
    height: 100%;
  }

  #ad {
    background: orange;
  }

  #pdf {
    background: #70DB55;
  }

  #function{
    background: blueviolet;
  }



</style>
