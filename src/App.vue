<template>
  <div id="app" class="app" align="center">
    <router-view></router-view>
  </div>
  </template>

<script>
import mine from './components/mine';
import edu from './components/edu';
import proj from './components/proj';
import com from './components/Command.vue';

export default{
 //name:'app',
  components:{
    mine,
    edu,
    proj,
    com
  }
}

</script>

<style scoped>
.app-1{
  font-size: 14px;
  font-family: 微软雅黑;
  color:#333333;
  width:702px;
  background-color: rgba(77, 77, 77, 0.02);
  border-color: #000;
}
.top{
  width: 702px;
  height: 140px;
  background-image: url('http://www.lagou.com//images/myresume/tou.png');
}

.top-photo img{
  position:relative;
  top:45px;
  width:115px;
  height:115px;
  border-radius:200px;
}
</style>
