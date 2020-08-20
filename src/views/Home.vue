<template>
    <div>
      <div class="con-header">
        <img  class="con-header-logo" src="../assets/light_chrome.png" width="40px" height="40px" >
        <span class="con-header-title">极简插件</span>
        <div class="demo-input-suffix">
        <el-input placeholder="请输入内容" prefix-icon="el-icon-search">
        </el-input>
</div>
      </div>
    </div>
</template>

<script>
  export default {
    name: '',
    data() {
      return {
        
      }
    }
  }
</script>

<style>
  *{
    margin: 0;
    padding: 0;
  }
  .con-header{
    width: 100%;
    height: 64px;
    background-color: #2C3742;
    /* vertical-align:-5px; */
    /* display: block; */
    position: relative;
  }
  .con-header-title{
    font-size: 30px;
    line-height: 64px;
    text-align: center;
    color: #ffffff;
    margin-left: 26px;
  }
  .con-header-logo{
    position:relative;
    top: 10px;
    margin-left: 219px;
  }
  .el-input__inner{
    width: 100px;
    display: inline-block;
    width: 276px; 
    height: 37px;
  }
</style>
