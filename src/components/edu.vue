<template>
  <div id="edu" class="edu">
    <div class="title">
      <div class="title-line"></div>
      <span class="title-name">教育经历</span>
      <div class="title-line11">
        <div class="title-line1" align="right"></div>
      </div>
    </div>
    <div id="edu-1">
      <div id="edu-1-img" align="left">
        <img src="http://www.lagou.com/i/image/M00/AD/50/Cgp3O1i1E6WANoUaAAAKhwbGKoI24.jpeg">
      </div>
      <div id="edu-1-middle">
        <span class="name">{{name}}</span><br>
        <span class="des">{{des}}</span>
      </div>
      <div id="edu-1-left" align="right">
        {{data}}
      </div>
    </div>

  </div>
</template>

<script type="text/ecmascript-6">
  export default{
    data(){
      return {
        name: '仲恺农业工程学院',
        des: '本科·计算机科学与技术',
        data: '2018年毕业（预计）'


      }
    }

  }
</script>

<style scoped>
  #edu {
    position: relative;
    width: 604px;
    height: 161px;
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

  #edu-1 {
    width: 604px;
  }

  #edu-1-img {
    position: absolute;
    width: 50px;;
  }

  #edu-1-middle {
    position: absolute;
    margin-left: 0px;
    width: 250px;
  }

  .name {
    font-size: 16px;
  }

  .des {
    color: #999;
  }

  img {
    width: 46px;
    height: 46px;
    border: 2px solid #eee;
  }
</style>
