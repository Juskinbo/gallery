<template>
  <div class="image__lazy">
    <el-image v-for="url in urls" :key="url" :src="url" lazy />
  </div>
</template>

<script lang="ts" setup>
const urls = [
  'https://s2.loli.net/2023/06/02/XylI2U3uJC47jxG.jpg',
  'https://s2.loli.net/2023/06/02/uJxcRiv6K4L8w9p.jpg',
  'https://s2.loli.net/2023/06/02/ThGCRNwulrsEBHI.jpg',
  'https://s2.loli.net/2023/06/02/dptlgnuKW4foE63.jpg',
  'https://s2.loli.net/2023/06/02/ogOFl8JkujmCtve.jpg',
  'https://s2.loli.net/2023/06/02/vywlrNLHUhsVdkI.jpg',
  'https://s2.loli.net/2023/06/02/OBinuqUGDW4zZXw.jpg',
  'https://s2.loli.net/2023/06/02/HqKztG1s4LrpTDQ.jpg',
  'https://s2.loli.net/2023/06/02/fghX2PB9HCJUsnq.jpg',
  'https://s2.loli.net/2023/06/02/87wgDMpRhj5CyGE.jpg',
  'https://s2.loli.net/2023/06/02/Mb1oxZJFVqnXkNz.jpg',
  'https://s2.loli.net/2023/06/02/KS6iUIlXr1B9xnv.jpg',
  'https://s2.loli.net/2023/06/02/aHuFZTwyUVmlBGX.jpg',
  'https://s2.loli.net/2023/06/02/BYOWGsto3k2TnEM.jpg',
  'https://s2.loli.net/2023/06/02/uUZamybHzv6Fe8Q.jpg',
  'https://s2.loli.net/2023/06/02/UgzOLqvnFtw2cPK.jpg',
  'https://s2.loli.net/2023/06/02/2iJapnEd5rSNfBc.jpg',
  'https://s2.loli.net/2023/06/02/sKXLDY1fFJqWdnt.jpg',
  'https://s2.loli.net/2023/06/02/TmiwQboRxOIGYuW.jpg',
]
</script>

<style scoped>
.image__lazy {
  height: 100%;
  overflow-y: auto;
}

.image__lazy .el-image {
  display: block;
  min-height: 200px;
  margin-bottom: 10px;
}

.image__lazy .el-image:last-child {
  margin-bottom: 0;
}
</style>
