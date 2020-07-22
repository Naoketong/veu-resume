<template>
  <el-container :style="style_container" class="h100">
    <Sider :style="sider_width"/>
    <el-container :style="style_container">
      <el-header v-show="header" class="page-header" height="64px">
        <Header ></Header>
      </el-header>
      <el-main class="page-mainer">
        <router-view></router-view>
      </el-main>
      <Footer />
    </el-container>
  </el-container>
</template>

<script>
import Header from "./BasicLayoutHeader.vue";
import Footer from "./BasicLayoutFooter.vue";
import Sider from "./BasicLayoutSider.vue";

export default {
  data() {
    return {
      style_container:'',
      sider_width:'',
      header:true,
    };
  },
  created(){
    this.layout();
  },
  methods:{
    layout(){
      this.screenWidth = document.body.clientWidth;
      console.log(this.screenWidth)
      if( this.screenWidth < 500){
        this.style_container = 'flex-wrap:wrap;'
        this.sider_width = 'width:100%;'
        this.header = false;
        // console.log('移动端')
      }else{
        // console.log('PC端')
      }
    },
  },
  components: {
    Header,
    Footer,
    Sider
  }
};
</script>

<style type="text/css" lang="less">
html,body{
  width:100%;
  height:100%;
}
.h100 {
  height: 100vh;
  // background-color: #f0f2f5;
}

.page-header {
  background-color: #fff;
  box-shadow: 0 2px 8px #f0f1f2;
  position: relative;
  z-index: 10;
  height: 64px;

  .page-header-title {
    font-size: 20px;
  }
}

.page-sider {
  position: relative;
  background-color: #5770ff;
  // background-color: #409EFF;
  // background-color:#5974D4;
  box-shadow: 2px 0 8px 0 rgba(29, 35, 41, 0.05);
  .el-menu {
    border-right: none;
  }
}
.page-siders{
  width:100%;
  background-color: #5770ff;
}

.page-mainer {
  padding: 0;
}



</style>
