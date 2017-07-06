<template>
    <div class="com">
      <div class="title">
        <div class="title-line"></div>
        <span class="title-name">自我描述</span>
        <div class="title-line11"><div class="title-line1" align="right"></div></div>
      </div>
<div class="photo">
  <img src="../assets/猪.jpg">
</div>
      <div class="detail">{{detail}}</div>
    </div>
</template>

<script type="text/ecmascript-6">
    export default{
      data(){
        return{
          detail:'本人有高度的责任心，学习上严谨务实，能吃苦耐劳，做事不半途而废，诚信待人，具有团队合作精神和协作精神，善于自我反思和自主学习.'
        }
      }
    }
</script>

<style scoped>
  .com{
    position: relative;
    width: 604px;
    height: 180px;
  }
  .title{
    width: 604px;
    height: 34px;
  }
  .title-line{
    position: absolute;
    width: 230px;
    height:0;
    margin-top: 11px;
    border-top: 1px solid #ededed;
  }

  .title-name{
    font-size:18px;
    padding:6px 24px;
    text-align: center;
    background-color: #eee;
    border-radius: 26px;
    margin: 0 13px;
  }

  .title-line11{
    position: absolute;
    top:11px;
    width: 970px;
    height: 3px;
  }
  .title-line1{
    width:228px;
    height: 0;

    border-top: 1px solid #ededed;
  }
img {
  position: absolute;
  top: 45px;
  left: 0px;
  width: 81px;
  height: 81px;
  border-radius: 200px;
}
  .detail{
    position: absolute;
    margin-left: 100px;
    top:50px;
    width:500px;
    text-align: left;
  }
</style>
