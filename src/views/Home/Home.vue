<template>
  <div class="home-container">
    <!-- 首页入口 -->
    <div class="home-entry">
      <div>
        <!-- 左侧分类 -->
        <HomeCategory />
        <!-- 轮播图 -->
        <HomeBanner />
      </div>
    </div>
    <!-- 新鲜好物 -->
    <HomeNew />
    <!-- 人气推荐 -->
    <HomeHot />
    <!-- 品牌推荐 -->
    <HomeBrand />
    <!-- 产品区块 -->
    <HomeProduct />
    <!-- 专题 -->
    <HomeSpecial />
  </div>
</template>

<script lang="ts" setup>
import HomeCategory from './components/home-category.vue';
import HomeBanner from './components/home-banner.vue';
import HomeNew from './components/home-new.vue';
import HomeHot from './components/home-hot.vue';
import HomeBrand from './components/home-brand.vue';
import HomeProduct from './components/home-product.vue';
import HomeSpecial from './components/home-special.vue';
</script>

<style scoped lang="less">
.home-container {
  .home-entry {
    position: relative;
    top: 0;
    left: 0;
    background-color: #f5f5f5;
    div {
      position: relative;
      top: 0;
      width: 1240px;
      height: 500px;
      margin: 0 auto;
    }
  }
}
</style>
