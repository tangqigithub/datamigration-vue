<template>
    <el-menu
      default-active="1"
      style="width: 170px">
      <a href="#carousel">
        <el-menu-item index="1">
          <i class="el-icon-box"></i>
          <span >技术采用</span>
        </el-menu-item>
      </a>
      <a href="#update-card">
        <el-menu-item index="2">
          <i class="el-icon-menu"></i>
          <span>最近更新</span>
        </el-menu-item>
      </a>
      <a href="#slogan">
        <el-menu-item index="3">
          <i class="el-icon-document"></i>
          <span>相关服务</span>
        </el-menu-item>
      </a>
      <a href="#about">
        <el-menu-item index="4">
          <i class="el-icon-setting"></i>
          <span>关于scrap</span>
        </el-menu-item>
      </a>
    </el-menu>
</template>

<script>
  export default {

  }
</script>

<style>
  a {
    text-decoration: none;
    color: inherit;
  }
</style>
