<template>
    <div id="mine" class="mine"  align="center">
      <p class="name">{{name}}</p>
      <p>{{L1}}</p>
      <p>{{L2}}</p>
      <p>{{L3}}</p>


    </div>
</template>

<script type="text/ecmascript-6">
    export default{
        data(){
          return{
            name:'李文珊',
            L1:'计算机科学与技术·仲恺农业工程学院',
            L2:'本科 应届毕业生 广州',
            L3:'18826496877     737308573@qq.com'
          }
        }

    }
</script>

<style scoped>
  .mine{
    position: relative;
    font-size:15px;
    font-family: 微软雅黑;
    color: rgba(12, 12, 12, 0.82);
    height: 230px;
  }
  .name{
    font-size:30px;
    color: #333333;

  }


</style>


