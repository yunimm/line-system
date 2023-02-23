<template>
  <div id="app">
    <!-- <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
    <router-view /> -->
    <el-container>
      <el-header class="el-header">header</el-header>
      <el-container class="container">
        <el-aside class="el-aside">a-side</el-aside>
        <el-main class="el-main">dlkfld</el-main>
      </el-container>
    </el-container>
  </div>
</template>

<style lang="scss">

.el-header {
  background-color: rgb(29, 54, 87);
}
.el-aside {
  background-color: rgb(95, 124, 124);
}
.container {
  height: calc(100vh - 60px);
}

</style>
