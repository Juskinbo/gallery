<template>
  <div class="common-layout">
    <el-container>
      <el-header>Header</el-header>
      <el-container>
        <el-aside width="20vw">Aside</el-aside>
        <el-main>
          <GalleryComponent />
        </el-main>
      </el-container>
    </el-container>
  </div>
</template>
<script setup lang="ts">
import GalleryComponent from './components/GalleryComponent.vue';


</script>
<style>
body {
  margin: 0;
}
html ,body,#app, .common-layout, .el-container {
  height: 100%;
}
.el-aside{
  padding: 20px;
}
</style>