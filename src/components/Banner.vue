<template>
  <div class="swiperDiv">
    <div class="swiper-container" v-if="bannerData &&bannerData.length>0">
      <div class="swiper-wrapper">
        <div class="swiper-slide">
          <img src="https://pic1.zhimg.com/v2-cacf8804161bc9932a5a269e2e33b0d3.jpg?source=8673f162" alt />
          <div class="info">
            <h3>手机或电脑上有哪些为残障人士出发的功能，后来被所有人便捷使用？</h3>
            <span>作者 / 夏冰莹</span>
          </div>
        </div>
        <div class="swiper-slide">
          <img src="https://pic1.zhimg.com/v2-d3d6166e38db0acfdc67b3d4e0e5dfd8.jpg?source=8673f162" alt />
          <div class="info">
            <h3>植物是怎么分类的？</h3>
            <span>作者 / 老牛头</span>
          </div>
        </div>
        <div class="swiper-slide">
          <img src="https://pic1.zhimg.com/v2-946bb634af794e759a988c24d57c12a9.jpg?source=8673f162" alt />
          <div class="info">
            <h3>汉语环境中「老公」这一称呼是如何演变的？</h3>
            <span>作者 / 丧心病狂刘老湿</span>
          </div>
        </div>
        <div class="swiper-slide">
          <img src="https://pic3.zhimg.com/v2-fc4ae893d24a9547896274a24f3b52eb.jpg?source=8673f162" alt />
          <div class="info">
            <h3>游泳运动员会在水里出事情吗?</h3>
            <span>作者 / 网易体育</span>
          </div>
        </div>
        <div class="swiper-slide">
          <img src="https://pic3.zhimg.com/v2-84e25bf6bbeb8c41638670f93b8a3a2c.jpg?source=8673f162" alt />
          <div class="info">
            <h3>在冰岛生活是怎样的体验？</h3>
            <span>作者 / 嘉倩</span>
          </div>
        </div>
      </div>
      <!-- 如果需要分页器 -->
      <div class="swiper-pagination"></div>
    </div>
  </div>
</template>
<script>
import Swiper from "swiper";
import "swiper/swiper.less";
import { watch, onMounted } from "vue";
function initSwiper() {
  new Swiper(".swiper-container", {
    loop: true,
    observer: true,
    pagination: {
      el: ".swiper-pagination"
    }
  });
}
export default {
  props: {
    bannerData: {
      type: Array
    }
  },
  methods: {
    handle(id) {
      this.$router.push(`/detail/${id}`);
    }
  },

  setup(props) {

    // onMounted
    onMounted(() => {
      let t = setTimeout(() => {
        initSwiper();
        clearTimeout(t);
      },2000);
    });

    watch(
      () => props.bannerData,
      () => initSwiper(),
      {
        immediate: true
      }
    );
  }
};
</script>
<style lang="less" scoped>


.swiper-container {
  width:100%;
  height: 6rem;
  overflow: hidden;
  background: #eee;

  .swiper-slide {
    position: relative;

    img {
      display: block;
      width: 100%;
    }

    .info {
      box-sizing: border-box;
      position: absolute;
      bottom: 0;
      left: 0;
      z-index: 10;
      padding: 0.2rem;
      width: 100%;
      color: #fff;
      background: linear-gradient(
        0,
        rgba(55, 86, 103, 0.5),
        rgba(55, 86, 103, 0)
      );

      h3 {
        font-size: 0.36rem;
        line-height: 0.6rem;
        white-space: nowrap;
        text-overflow: ellipsis;
        overflow: hidden;
      }

      span {
        font-size: 0.28rem;
        line-height: 0.6rem;
      }
    }
  }

  .swiper-pagination{
    height:20px;
  }
}
</style>