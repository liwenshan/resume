<template>
  <div class="proj">
    <div class="title">
      <div class="title-line"></div>
      <span class="title-name">项目经历</span>
      <div class="title-line11">
        <div class="title-line1" align="right"></div>
      </div>
    </div>
    <div align="left" class="proj-detail">
      <ul>
        <li v-for="proj in projs">
          <div class="li">
            <div class="proj-name">
              {{proj.name}}
            </div>
            <div class="proj-time" align="right">
              {{proj.time}}
            </div>
            <div class="proj-mine">
              {{proj.mine}}
            </div>
            <br>
            <div class="proj-detail">
              {{proj.detail}}
            </div>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<script type="text/ecmascript-6">
  export default{
    data(){
      return {
        projs: [
          {
            name: 'web手机商城',
            time: '2017.05-2017.05',
            mine: '商品详情页面、店铺页面前端，实现卖家管理店铺功能',
            detail: '该项目由小组3个人团队开发，按模块分配任务，每个人都要编写其负责模块的前端和后台代码。通过git来实现团队开发。从项目文档需求分析到，概要设计，详细设计，到最终编码测试的整个过程。我们采用的是原型法，通过描绘出核心功能进行拓展。前端界面设计主要参考小米商城。后台采用MVC+JAVABEAN进行编写。'

          }
        ]

      }
    }
  }
</script>

<style scoped>
  .proj {
    position: relative;
    width: 680px;
  }

  .title {
    width: 604px;
    height: 34px;
  }

  .title-line {
    position: absolute;
    width: 230px;
    height: 0;
    margin-top: 11px;
    border-top: 1px solid #ededed;
  }

  .title-name {
    font-size: 18px;
    padding: 6px 24px;
    text-align: center;
    background-color: #eee;
    border-radius: 26px;
    margin: 0 13px;
  }

  .title-line11 {
    position: absolute;
    top: 11px;
    width: 970px;
    height: 3px;
  }

  .title-line1 {
    width: 228px;
    height: 0;

    border-top: 1px solid #ededed;
  }

  .proj-detail {
    height: 230px;
  }

  ul {
    list-style: none;
  }

  .li {
    width: 604px;
  }

  .proj-name {
    position: absolute;
    width: 100px;
    font-size: 16px;
  }

  .li .proj-time {
    width: 604px;

    color: #999;
  }

  .proj-mine {
    color: #999;
  }
</style>
