<template>
  <div class="app-1">
    <div class="top" align="center">
      <div class="top-photo">
        <img src="../assets/猪.jpg" width="120" height="120">
      </div>
    </div>

    <mine></mine>
    <edu></edu>
    <proj></proj>
    <Command></Command>

    <div class="test-btn">
      <a href="javascript:;" @click="goHello">I am a button</a>
    </div>

  </div>
</template>
<script>
  import Command from '@/components/Command'
  import edu from '@/components/edu'
  import mine from '@/components/mine'
  import proj from '@/components/proj'

  export default {
    name: 'Home',
    components: {
      Command,
      edu,
      mine,
      proj
    },
    methods: {
      goHello() {
        this.$router.push('/hello')
      }
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
