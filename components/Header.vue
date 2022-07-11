<template lang="">
  <el-header
    style="
      text-align: right;
      font-size: 12px;
      position: fixed;
      width: 100%;
      left: 0;
      top: 0;
      z-index: 1500;
      height: 80px;
      padding-bottom: 80px;
    "
  >
    <div>
      <el-link href="/" target="_blank">default</el-link>
      <el-link href="/">home</el-link>
      <el-link href="/blog" type="primary">blog</el-link>
      <el-link href="/blog/posts" type="success">posts</el-link>
      <el-link type="warning">warning</el-link>
      <el-link type="danger">danger</el-link>
      <el-link type="info">info</el-link>
      <el-dropdown>
        <i class="el-icon-setting" style="margin-right: 15px"></i>
        <el-dropdown-menu slot="dropdown">
          <el-dropdown-item>View</el-dropdown-item>
          <el-dropdown-item>Add</el-dropdown-item>
          <el-dropdown-item>Delete</el-dropdown-item>
        </el-dropdown-menu>
      </el-dropdown>
      <span>Tom</span>
    </div>
  </el-header>
</template>
<script>
export default {}
</script>
<style lang=""></style>
