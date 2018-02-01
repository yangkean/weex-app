<template>
  <!-- <div class="wrapper">
    <image :src="logo" class="logo"></image>
    <text class="greeting">The environment is ready!</text>
    <text class="message">这是杨可安的第一个 App</text>
    <switch @change="onchange"></switch>
    <div class="dialog" v-if="appear">
      <text>hello，你把按钮打开了</text>
    </div>
  </div> -->
  <div class="wrapper">
    <text class="iconfont">杨</text>
    <home-header></home-header>
    <!-- 此处 offset-accuracy 是触发 scroll 事件所需要的垂直偏移距离 -->
    <scroller class="main-list" offset-accuracy="300px">
      <refresher></refresher>
      <div class="cell-button" @click="jumpWeb('https://m.you.163.com')">
        <yx-slider :imageList="YXBanners"></yx-slider>
      </div>
      <div class="cell-button">
        <block-1 :title="block1.title" :items="block1.items"></block-1>
      </div>
    </scroller>
  </div>
</template>

<script>
import util from '../../src/assets/util';
import HomeHeader from '../components/home-header';
import Refresher from '../com'
</script>

<style scoped>
.iconfont {
  font-family: iconfont;
}
.main-list {
  position: fixed;
  top: 168px;
  bottom: 90px;
  left: 0;
  right: 0;
}
</style>
