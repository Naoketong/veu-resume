<template>
  <div class="home-page">
    <div class="user-section">
      <el-row :gutter="40">
        <el-col :lg="12">
          <div class="grid-content">
            <h3 class="sub-title">能力简介</h3>
            <ul class="user-power">
              <li>
                1、熟练使用
                HTML、CSS、JavaScript，能高效率还原设计稿、动画及业务逻辑交互。
              </li>
              <li>2、掌握使用前端框架，jQuery、 Vue、Element Ui。</li>
              <li>3、熟悉移动端开发，能兼容移动版H5、微信小程序移动版产品。</li>
              <li>4、熟悉前端工程化搭建、webpack、Glup、Git。</li>
              <li>
                5、熟悉后端 Node.js，能操作
                Express、Koa能快速启动项目、独立敏捷开发。
              </li>
            </ul>
          </div>
        </el-col>
        <el-col :lg="12">
          <div class="grid-content">
            <h3 class="sub-title">技能清单</h3>
            <ul class="user-power">
              <li>
                Web开发：
                <el-tag size="small">HTML</el-tag>
                <el-tag size="small">CSS</el-tag>
                <el-tag size="small" type="danger">JavaScript</el-tag>
              </li>
              <li>
                Web框架：
                <el-tag size="small" type="danger">Node.js</el-tag>
                <el-tag size="small">Express</el-tag>
                <el-tag size="small">Koa2</el-tag>
              </li>
              <li>
                前端框架：
                <el-tag size="small">jQuery</el-tag>
                <el-tag size="small" type="danger">Vue.js</el-tag>
                <el-tag size="small">Element UI</el-tag>
                <el-tag size="small" type="danger">微信小程序</el-tag>
              </li>
              <li>
                前端工具：
                <el-tag size="small">Webpack</el-tag>
                <el-tag size="small">Gulp</el-tag>
                <el-tag size="small">Vue CLI3</el-tag>
              </li>
              <li>
                数据存储：
                <el-tag size="small">MySQL</el-tag>
              </li>
              <li>
                版本管理：
                <el-tag size="small">Git</el-tag>
                <el-tag size="small">Github</el-tag>
              </li>
            </ul>
          </div>
        </el-col>
      </el-row>
    </div>
    <div class="work-section">
      <h3 class="sub-title">项目经验</h3>
      <div class="block">
        <el-timeline>
          <el-timeline-item
            type="success"
            timestamp="2019.6～ 2020.4 扎克斯科技 - 前端研发，参与外包项目，负责方案执行和提供技术支持。"
            placement="top"
          >
            <el-row :gutter="40">
              <el-col :lg="12">
                <div class="grid-content">
                  <el-card>
                    <h4 class="card-title">
                      汇典出行（扎克斯外包项目）
                    </h4>
                    <p class="card-text">
                      <span>项目描述：</span>
                      租车公司为了更好方便管理内部事务以及拓展客户群体，和我司合作，开发一套移动端租车平台，并接入公司租车后台系统，需要一套承接这类订单的统计、反馈的管理系统
                    </p>
                    <p class="card-text">
                      <span>项目成就：</span>
                      通过本项目，在 Node.js 环境中使用 Express快速搭建服务框架，在vue框架使用element搭建后台页面实现逻辑交互和状态切换，
                      使用微信小程序作为移动端，利用极大的流量支撑和海量用户，有利于扩大客户群体，在三个项目互相调配的过程中懂得了前后端之间是如何相互协调互相妥协的，
                      页面是如何与服务端进行交互影响数据变化，移动端上传的数据是如何呈现给后台的。
                    </p>
                    <a
                      class="card-case"
                      href="https://www.yuque.com/naokotong/kb/uhprlz"
                      >
                      我是地址（语雀）
                    </a>
                    <a
                      class="card-case"
                      href="https://github.com/Naoketong/hui-canon_node"
                      >
                      我是地址（后端）
                    </a>
                    <a
                      class="card-case"
                      href="https://github.com/Naoketong/hui-canon_vue"
                      >
                      我是地址（后台样式）
                    </a>
                    <a
                      class="card-case"
                      href="https://github.com/Naoketong/hui-canon_xcx"
                      >
                      我是地址（移动端）
                    </a>
                  </el-card>
                </div>
              </el-col>

              <el-col :lg="12">
                <div class="grid-content">
                  <el-card>
                    <h4 class="card-title">
                      留音社（扎克斯外包项目）
                    </h4>
                    <p class="card-text">
                      <span>项目描述：</span>留音社是一家位于广州增城的，面向 7
                      ～ 16 岁儿童音乐培训中心，目前主要有钢琴、声乐、舞蹈
                      几个品类的课程。 学员的统计、上课管理都用 Excel
                      和纸张来签到打勾记录，每次即将上课时候都需要人工电话预约和确认是否请假。
                      需要一个后台系统统计学员的各种情况和微信小程序方便用户请假和预约
                    </p>
                    <p class="card-text">
                      <span>项目成就：</span>
                      通过本项目，在 Node.js 环境中使用 Express 快速搭建服务框架，
                      在vue框架使用element搭建后台页面实现逻辑交互和状态切换， 
                      使用微信小程序作为移动端，方便客户对签到请假预约课程等操作，
                      在三个项目互相调配的过程中懂得了前后端之间是如何相互协调互相妥协的， 
                      页面是如何与服务端进行交互影响数据变化，移动端上传的数据是如何呈现给后台的。 
                    </p>
                    <a
                      class="card-case"
                      href="https://github.com/Naoketong/liuyinshe_nodejs"
                      >
                      我是地址（后端）
                    </a>
                    <a
                      class="card-case"
                      href="https://github.com/Naoketong/liuyinshe_vue"
                      >
                      我是地址（后台样式）
                    </a>
                    <a
                      class="card-case"
                      href="https://github.com/Naoketong/liuyinshe_v1-xcx"
                      >我是地址（移动端）
                    </a>
                  </el-card>
                </div>
              </el-col>
            </el-row>
          </el-timeline-item>
        </el-timeline>
      </div>
      <div class="block">
        <el-timeline>
          <el-timeline-item
            type="success"
            timestamp="2019.5～ 2020.4 扎克斯科技 - 前端研发，负责前端项目方案执行和配合开发者进行技术支持。"
            placement="top"
          >
            <el-row :gutter="40">
              <el-col :lg="12">
                <div class="grid-content">
                  <el-card>
                    <h4 class="card-title">
                      信息发布系统（ 极客学院教研项目 ）
                    </h4>
                    <p class="card-text">
                      <span>项目描述：</span
                      >极客学院的信息发布系统，通过后台配置的内容在前台中进行展示，支撑企业的信息发布和信息管理，
                      运营人员会定期发布极客学院的新的动态及技术内容帮助大家及时的掌握前沿技术动态，更好的学习规划。
                      为此需要一套信息管理发布系统来方便对他的内容进行发布、修改、删帖和分类等。
                    </p>
                    <p class="card-text">
                      <span>项目成就：</span>通过本项目，对 Node.js API
                      有更深入的了解，接下来可以完成 80% 的内容 API 设计。同时对
                      Vue 、Vue-router 及 Element-Ui
                      有实战行的应用。在技术点上还涉及到 Vue-CLI 和其他后端框架
                      Express 的融合。
                    </p>
                    <a
                      class="card-case"
                      href="https://github.com/Naoketong/backstage-ims"
                      >我是地址</a
                    >
                  </el-card>
                </div>
              </el-col>
              <el-col :lg="12">
                <div class="grid-content">
                  <el-card>
                    <h4 class="card-title">
                      销售管理系统（ 极客学院教研项目）
                    </h4>
                    <p class="card-text">
                      <span>项目描述：</span
                      >企业吸引更多的消费者，和广告公司合作做出各类精良的营销落地页，并在各个社交、媒体平台中进行投放。为了更好地获取广告信息，指导投放营销，需要一套承接这类营销落地页收集用户的购买行为信息，并进行跟踪、统计、反馈的管理系统。
                    </p>
                    <p class="card-text">
                      <span>项目成就：</span>通过本项目，在 Node.js 环境中使用
                      Express 快速搭建服务框架，并熟悉简单的 MySQL
                      数据库操作，可以完成数据的增删改查以及连表查询数据。同时，我们还对后端中
                      MVC
                      有深入的了解和实际的运用，懂得了在一个项目中数据是如何从数据库渲染到页面，页面是如何与服务端进行交互从而影响数据的变化。
                    </p>
                    <a
                      class="card-case"
                      href="https://github.com/Naoketong/porschr-crm"
                      >我是地址</a
                    >
                  </el-card>
                </div>
              </el-col>
            </el-row>
          </el-timeline-item>
        </el-timeline>
      </div>

      <div class="block">
        <el-timeline>
          <el-timeline-item
            type="success"
            timestamp="2019.5～ 2020.4 扎克斯科技 - 前端研发，负责前端项目方案执行和配合开发者进行技术支持。"
            placement="top"
          >
            <el-row :gutter="40">
              <el-col :lg="12">
                <div class="grid-content">
                  <el-card>
                    <h4 class="card-title">
                      目标与成就管理系统（ 扎克斯外包项目 ）
                    </h4>
                    <p class="card-text">
                      <span>项目描述：</span>OKR
                      为探月学院内部研发的目标管理的系统，能够将目标管理自上而下贯穿到基层。通过要设定一个“目标”（Objective），然后，设定若干可以量化的“关键结果”（Key
                      Results），用来帮助实现目标。
                    </p>
                    <p class="card-text">
                      <span>项目成就：</span>
                      通过本项目首先对 OKR
                      有一个初步的认识，之前没有丁点概念，也熟悉企业的管理机制。在项目中使用
                      Koa2 来构建简易的 API， 对 Nodejs API
                      的生产有更熟悉的运用，同时对小程序开发有一定的了解，能够完成负责业务场景下的小程序研发工作。
                    </p>
                  </el-card>
                </div>
              </el-col>

              <el-col :lg="12">
                <div class="grid-content">
                  <el-card>
                    <h4 class="card-title">
                      微信小程序音视频云开发（ 个人项目 ）
                    </h4>
                    <p class="card-text">
                      <span>项目描述：</span
                      >使用云开发音视频小程序，在腾讯云平台上对小程序的数据进行存储与操作，仿照微信朋友圈，完成文字、音视频的发布与评论功能。
                    </p>
                    <p class="card-text">
                      <span>项目成就：</span>
                      对微信小程序开发中云函数、云存储、云数据库集合的有进一步的了解，同时给我带来最大的影响是，前端在构建自己独立的项目时候，不需要依赖后端的接口来实现数据的获取和存储，或者一直在测试着自己的本地的假数据，可以独立完成项目开发。
                    </p>
                  </el-card>
                </div>
              </el-col>
            </el-row>
          </el-timeline-item>
        </el-timeline>
      </div>

      <div class="block">
        <el-timeline>
          <el-timeline-item
            type="success"
            timestamp="2018.10～ 2019.5 扎克斯科技 - 前端研发，负责项目营销活动页和专题页等展示型网页样式开发。"
            placement="top"
          >
            <el-row :gutter="40">
              <el-col :lg="12">
                <div class="grid-content">
                  <el-card>
                    <h4 class="card-title">营销活动页（外包项目）</h4>
                    <p class="card-text">
                      <span>项目描述：</span
                      >完成营销、活动、专题项目、后台项目的样式和交互、后端API设计和逻辑，服务过的公司有：极客学院、当代家庭教育、留音社等等，主要使用
                      HTML、CSS、JavaScript、vue和node.js
                      完成页面样式和交互开发。
                    </p>
                    <p class="card-text">
                      <span>项目成就：</span>
                      通过与甲方数次的合作，
                      通过多次外包的实际操作经验，增强了自己是责任心、学会了换位思考、能对甲方的需求能够快速反应，能够精准、高效的完成甲方的需求。不仅增加了工作的紧迫感与危机感，同时体会到在以后的工作中，更应该进一步加强自身业务素质的提高，
                      以适应自身岗位要求不断改进的需要。要不断加强相关理论知识的学习力度，进一步提升个人的技术理论水平
                    </p>
                    <a
                      class="card-case"
                      href="https://naoketong.github.io/intouch_a/"
                    >
                      极客学院 因特驰
                    </a>
                    <a
                      class="card-case"
                      href="http://yx.ddjtjyzds.com/v2/index.html?hmsr=bdsem_zds_all_1037_pc"
                    >
                      当代家庭教育 PC端
                    </a>
                    <a
                      class="card-case"
                      href="https://naoketong.github.io/ddjy-home_move/"
                    >
                      当代家庭教育 移动端
                    </a>
                  </el-card>
                </div>
              </el-col>

              <el-col :lg="12">
                <div class="grid-content">
                  <el-card>
                    <h4 class="card-title">营销活动页开发</h4>
                    <p class="card-text">
                      <span>项目描述：</span>主要使用
                      HTML、CSS、JavaScript完成页面样式和交互开发，vue和node.js为框架，完成营销、活动、专题项目的样式、交互与后台逻辑。
                    </p>
                    <p class="card-text">
                      <span>项目成就：</span
                      >通过多个项目的训练，对设计稿的还原度以及交付效率有质的提升，能给高效、快速地
                      1 : 1 还原设计文件，同时 JavaScript
                      的语感提升为之后的多页面项目研发打下基础。
                    </p>
                    <a class="card-case" @click="drawer = true" type="primary"
                      >点我看看作品案例</a
                    >
                    <!---抽屉-->
                    <el-drawer
                      title="案例列表 Case list"
                      :visible.sync="drawer"
                      :with-header="false"
                    >
                      <ul class="panel-list">
                        <li class="panel-item">
                          <i class="el-icon-star-on" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/intouch_a/"
                            class="panel-item-title"
                            >因特驰／极客学院</a
                          >
                        </li>
                        <li class="panel-item">
                          <i class="el-icon-star-on" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/ddjy-home_move/"
                            class="panel-item-title"
                            >当代家庭教育 移动端页面</a
                          >
                        </li>
                        <li class="panel-item">
                          <i class="el-icon-star-on" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/family_education/"
                            class="panel-item-title"
                            >当代家庭教育官网(第一版)</a
                          >
                        </li>
                        <li class="panel-item">
                          <i class="el-icon-star-on" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/ddjy-home_page/"
                            class="panel-item-title"
                            >当代家庭教育官网(第二版)</a
                          >
                        </li>
                        <li class="panel-item">
                          <i class="el-icon-s-help" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/shidi_group/"
                            class="panel-item-title"
                            >实地集团 官网</a
                          >
                        </li>
                        <li class="panel-item">
                          <i class="el-icon-s-help" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/ali-school-Page/"
                            class="panel-item-title"
                            >alt school 官网页面</a
                          >
                        </li>
                        <li class="panel-item">
                          <i class="el-icon-star-on" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/family_education-02/"
                            class="panel-item-title"
                            >当代家庭教育 PC端</a
                          >
                        </li>
                        <li class="panel-item">
                          <i
                            class="el-icon-picture-outline-round"
                            style="color:#fff;"
                          ></i>
                          <a
                            href="https://naoketong.github.io/originalit_appreciate/"
                            class="panel-item-title"
                            >匠心大赏</a
                          >
                        </li>
                        <li class="panel-item">
                          <i class="el-icon-s-help" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/jike_page-home/"
                            class="panel-item-title"
                            >极客学院首页</a
                          >
                        </li>
                        <li class="panel-item">
                          <i
                            class="el-icon-picture-outline-round"
                            style="color:#fff;"
                          ></i>
                          <a
                            href="https://github.com/Naoketong/V2EX"
                            class="panel-item-title"
                            >仿V2EX小程序</a
                          >
                        </li>
                        <li class="panel-item">
                          <i class="el-icon-bell" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/xiaomi/"
                            class="panel-item-title"
                            >小米官网</a
                          >
                        </li>
                        <li class="panel-item">
                          <i class="el-icon-s-help" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/douying/"
                            class="panel-item-title"
                            >抖音官网</a
                          >
                        </li>

                        <li class="panel-item">
                          <i class="el-icon-s-help" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/jike---wiki/"
                            class="panel-item-title"
                            >极客 wiki页面</a
                          >
                        </li>
                        <li class="panel-item">
                          <i class="el-icon-s-help" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/UI-UX-design/"
                            class="panel-item-title"
                            >极客学院UI/UX就业班</a
                          >
                        </li>

                        <li class="panel-item">
                          <i class="el-icon-cold-drink" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/University_cooperation/"
                            class="panel-item-title"
                            >极客学院&山东工商学院</a
                          >
                        </li>
                        <li class="panel-item">
                          <i class="el-icon-s-help" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/jianshu/"
                            class="panel-item-title"
                            >简书官网</a
                          >
                        </li>
                        <li class="panel-item">
                          <i class="el-icon-s-help" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/New-Qualcomm-subject/"
                            class="panel-item-title"
                            >高通合作</a
                          >
                        </li>
                        <li class="panel-item">
                          <i class="el-icon-cold-drink" style="color:#fff;"></i>
                          <a
                            href="https://github.com/Naoketong/go-kart"
                            class="panel-item-title"
                            >卡丁车之家 （部分）</a
                          >
                        </li>
                        <li class="panel-item">
                          <i class="el-icon-s-help" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/youke-01/"
                            class="panel-item-title"
                            >优课云纺</a
                          >
                        </li>
                        <li class="panel-item">
                          <i
                            class="el-icon-picture-outline-round"
                            style="color:#fff;"
                          ></i>
                          <a
                            href="https://naoketong.github.io/huaishou/"
                            class="panel-item-title"
                            >快手视频</a
                          >
                        </li>

                        <li class="panel-item">
                          <i class="el-icon-s-help" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/Su-Jin/"
                            class="panel-item-title"
                            >素锦博客首页</a
                          >
                        </li>
                        <li class="panel-item">
                          <i
                            class="el-icon-goblet-full"
                            style="color:#fff;"
                          ></i>
                          <a
                            href="https://naoketong.github.io/Microsoft-jikexueyuan/"
                            class="panel-item-title"
                            >微软&极客学院合作</a
                          >
                        </li>
                        <li class="panel-item">
                          <i class="el-icon-setting" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/jikexueyuan--zhiye-01/"
                            class="panel-item-title"
                            >极客学院 职业首页</a
                          >
                        </li>
                        <li class="panel-item">
                          <i
                            class="el-icon-goblet-full"
                            style="color:#fff;"
                          ></i>
                          <a
                            href="https://naoketong.github.io/jike_baidu-Ai/"
                            class="panel-item-title"
                            >百度Ai页面</a
                          >
                        </li>
                        <li class="panel-item">
                          <i class="el-icon-s-goods" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/Double-Eleven/"
                            class="panel-item-title"
                            >阿里云&极客学院 联合举办</a
                          >
                        </li>
                        <li class="panel-item">
                          <i class="el-icon-s-goods" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/Aliyun_01/"
                            class="panel-item-title"
                            >阿里云 atc 1号</a
                          >
                        </li>

                        <li class="panel-item">
                          <i class="el-icon-s-check" style="color:#fff;"></i>
                          <a
                            href="https://naoketong.github.io/renzheng-01/"
                            class="panel-item-title"
                            >个人认证页面交互</a
                          >
                        </li>
                      </ul>
                    </el-drawer>
                  </el-card>
                </div>
              </el-col>
            </el-row>
          </el-timeline-item>
        </el-timeline>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      drawer: false,
      direction: "rtl"
    };
  },
  methods: {},
  components: {}
};
</script>

<style type="text/css" lang="less" scoped>
.home-page {
  padding: 40px;

  .sub-title {
    font-size: 18px;
    margin-bottom: 16px;
  }

  .card-title {
    font-size: 16px;
    margin-bottom: 8px;
  }

  .card-text {
    font-size: 14px;
    color: #666;
    margin: 8px 0;
    span {
      font-size: 14px;
      color: #333;
      font-weight: 600;
      display: block;
    }
  }
  .card-case {
    display: inline-block;
    /* padding:5px; */
    /* border-radius: 8px; */
    /* background-color: #409EFF; */
    /* color:#fff; */
    font-size: 14px;
    color: #409eff;
    font-weight: 400;
    text-decoration: none;
    margin-right: 20px;
    cursor: pointer;
  }
  .card-case-button {
    color: #fff;
  }
  .user-power {
    list-style: none;
  }

  .grid-content {
    margin-bottom: 20px;
    font-size: 14px;
    line-height: 2;
  }

  .el-tag {
    margin-right: 8px;
  }
}
.panel-list {
  padding: 0 20px;
  list-style: none;
  .panel-item {
    display: inline-block;
    margin: 6px 6px 6px 0;
    cursor: pointer;
    border-radius: 8px;
    padding: 5px 10px;
    background-color: #409eff;
    .panel-item-title {
      font-size: 13px;
      color: #f2f6fc;
      margin-left: 5px;
    }
  }
  .panel-item:hover {
    opacity: 0.75;
    transition: all 0.2s ease;
  }
  .panel-item:nth-child(2n) {
    background-color: #67c23a;
  }
  .panel-item:nth-child(3n) {
    background-color: #e6a23c;
  }
  .panel-item:nth-child(4n) {
    background-color: #f56c6c;
  }
  .panel-item:nth-child(5n) {
    background-color: #6c708d;
  }
}
</style>
