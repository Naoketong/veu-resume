<template>
  <el-aside class="page-sider" style="">
    <div class="user-info">
      <div class="user-avatar">
        <img class="user-avatar-png" src="@/assets/avatar-1.png" />
      </div>
      <p class="user-name">董钊</p>
      <p class="user-status">Hello World！</p>
    </div>
    <div class="user-info">
      <div class="user-info-title">个人信息</div>
      <div class="user-info-text">
        <i class="el-icon-phone"></i>
        <span>联系方式：13825409682</span>
      </div>
      <div class="user-info-text">
        <i class="el-icon-bank-card"></i>
        <span>邮箱：103790874@qq.com</span>
      </div>
      <div class="user-info-text">
        <i class="el-icon-trophy"></i>
        <span>毕业学校：广东理工学院</span>
      </div>
      <div class="user-info-text">
        <i class="el-icon-tickets"></i>
        <span>毕业专业：计算机应用技术</span>
      </div>
      <div class="user-info-text">
        <i class="el-icon-present"></i>
        <span>出生年月：1995.02.09<!-- （广州） --></span>
      </div>

      <div class="user-info-text">
        <i class="el-icon-wind-power"></i>
        <span>应聘职位：前端研发工程师</span>
      </div>
      <div class="user-info-text">
        <i class="el-icon-position"></i>
        <span
          >GitHub:
          <a style="color: #F2F6FC;" href="https://github.com/Naoketong">点我点我</a>
        </span>
      </div>

      <div class="user-info-text">
        <i class="el-icon-bank-card"></i>
        <span>期望月薪：8～10k</span>
      </div>
       <div class="user-info-text">
        <i class="el-icon-tickets"></i>
        <span>工作经验：1 ～ 2年</span>
      </div>
    </div>
   
  </el-aside>
</template>

<script>
export default {
  props: {},
  components: {}
};
</script>

<style type="text/css" lang="less">
.page-sider {
  // display: none;
  position: relative;
  box-shadow: 2px 0 8px 0 rgba(29, 35, 41, 0.05);
  transition: all 0.2s ease;
  width: 240px;
  color: #fff;
  padding: 40px;
  padding-top: 20px;
  .user-info {
    margin: 40px 0;
    .user-info-title {
      font-size: 16px;
      font-weight: 600;
      margin-bottom: 8px;
    }
    .user-info-text {
      font-size: 14px;
      line-height: 2;
      i {
        margin-right: 8px;
        vertical-align: middle;
      }
      span {
        vertical-align: middle;
      }
    }
  }
  .user-avatar {
    .user-avatar-png {
      display: block;
      width: 130px;
      height: 130px;
      margin: 0 auto 20px;
      // box-shadow: 2px 0 8px 0 rgba(29, 35, 41, 0.05);
      border-radius: 50%;
      background-color: #fff;
    }
  }
  .user-name {
    font-size: 24px;
    font-weight: 500;
    text-align: center;
  }
  .user-status {
    margin-top: 8px;
    font-size: 16px;
    font-weight: 400;
    text-align: center;
  }
}
a {
  text-decoration: none;
}
</style>
