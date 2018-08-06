<template>
  <div class="header">
    <div class="header-left">
      <div class="iconfont header-left-icon">&#xe600;</div>
    </div>
    <div class="header-input" >
      <div class="header-input-text"><span class="iconfont">&#xe741;</span>请输入城市/主题</div></div>
    <div class="header-right">城市
    <span class="iconfont">&#xe601;</span></div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style scoped lang="less">
  @import "../../../assets/styles/varibles.less";
  .header{
    height: 40px;
    display: flex;
    font-size: 18px;
    background-color:@bgColor;
  }
  .header-left{
    margin-top: 10px;
    margin-left: 10px;
    width: 25px;
    float: left;
  }
  .header-left-icon{
    position:absolute
  }
  .header-right{
    width: 60px;
    float: right;
    margin-top: 10px;
    text-align: center;
  }
  .header-input{
    flex:1;
    background: white;
    margin-top: 5px;
    margin-left: 2px;
    text-align: center;
    border-radius: 5px;
    margin-bottom: 5px;
  }
  .header-input-text{
    margin-top: 5px;
  }
</style>
