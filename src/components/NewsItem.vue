<template>
  <div>
    <!-- <div v-for="item in news.stories" :key="item">
      <router-link :to="{path:`/detail/${item.id}`}" class="newsItem">
        <div class="con">
          <h4>{{item.title}}</h4>
          <span>{{item.hint}}</span>
        </div>
        <div class="pic">
          <img :src="item.images[0]" alt />
        </div>
      </router-link>
    </div> -->
    <div >
      <router-link :to="{path:`/detail/9731647`}" class="newsItem">
        <div class="con">
          <h4>国家卫健委称新冠疫苗为全民免费提供，这一成本会有多大？</h4>
          <span>庄有猫 · 4 分钟阅读</span>
        </div>
        <div class="pic">
          <img src="https://pic4.zhimg.com/v2-606d7311505517ea2917f52151e00c34.jpg?source=8673f162" alt />
        </div>
      </router-link>
      <a class="newsItem">
        <div class="con">
          <h4>野生动物吃鱼不会被刺卡住吗？</h4>
          <span>苏澄宇 · 3 分钟阅读</span>
        </div>
        <div class="pic">
          <img src="https://pic1.zhimg.com/v2-3624517ab701febfbd97cbcb85eea328.jpg?source=8673f162" alt />
        </div>
      </a>
      <a class="newsItem">
        <div class="con">
          <h4>为什么人会觉得二维东西是立体的？</h4>
          <span>fly qq · 1 分钟阅读</span>
        </div>
        <div class="pic">
          <img src="https://pic4.zhimg.com/v2-39220f356d84205e6e38dd4403a77d43.jpg?source=8673f162" alt />
        </div>
      </a>
      <a class="newsItem">
        <div class="con">
          <h4>《火影忍者》中，有哪些令你意难平的战斗？</h4>
          <span>锦曦日 · 3 分钟阅读</span>
        </div>
        <div class="pic">
          <img src="https://pic4.zhimg.com/v2-96613b95ab213980df87ada878a3152b.jpg?source=8673f162" alt />
        </div>
      </a>
      <a class="newsItem">
        <div class="con">
          <h4>如何完成标准的深蹲？</h4>
          <span>Valen · 7 分钟阅读</span>
        </div>
        <div class="pic">
          <img src="https://pic4.zhimg.com/v2-89e2d3f5f185a6e8f5b15c3a0f5728fb.jpg?source=8673f162" alt />
        </div>
      </a>
      <a class="newsItem">
        <div class="con">
          <h4>瞎扯 · 如何正确地吐槽</h4>
          <span>VOL.2563</span>
        </div>
        <div class="pic">
          <img src="https://pic4.zhimg.com/v2-e59b951ad15e86eb0beace6288237e16.jpg?source=8673f162" alt />
        </div>
      </a>
    </div>
  </div>
</template>
<script>
export default {
  props: ["news"],
  setup(props,two){
    /*
      [
        {"image_hue":"0x373c4f","title":"国家卫健委称新冠疫苗为全民免费提供，这一成本会有多大？","url":"https://daily.zhihu.com/story/9731638","hint":"庄有猫 · 4 分钟阅读","ga_prefix":"010407","images":["https://pic4.zhimg.com/v2-606d7311505517ea2917f52151e00c34.jpg?source=8673f162"],"type":0,"id":9731638},

        {"image_hue":"0x172121","title":"野生动物吃鱼不会被刺卡住吗？","url":"https://daily.zhihu.com/story/9731647","hint":"苏澄宇 · 3 分钟阅读","ga_prefix":"010407","images":["https://pic1.zhimg.com/v2-3624517ab701febfbd97cbcb85eea328.jpg?source=8673f162"],"type":0,"id":9731647},

        {"image_hue":"0x806a2d","title":"为什么人会觉得二维东西是立体的？","url":"https://daily.zhihu.com/story/9731635","hint":"fly qq · 1 分钟阅读","ga_prefix":"010407","images":["https://pic4.zhimg.com/v2-39220f356d84205e6e38dd4403a77d43.jpg?source=8673f162"],"type":0,"id":9731635},

        {"image_hue":"0xb38c70","title":"《火影忍者》中，有哪些令你意难平的战斗？","url":"https://daily.zhihu.com/story/9731653","hint":"锦曦日 · 3 分钟阅读","ga_prefix":"010407","images":["https://pic4.zhimg.com/v2-96613b95ab213980df87ada878a3152b.jpg?source=8673f162"],"type":0,"id":9731653},

        {"image_hue":"0x3f4530","title":"如何完成标准的深蹲？","url":"https://daily.zhihu.com/story/9731642","hint":"Valen · 7 分钟阅读","ga_prefix":"010407","images":["https://pic4.zhimg.com/v2-89e2d3f5f185a6e8f5b15c3a0f5728fb.jpg?source=8673f162"],"type":0,"id":9731642},

        {"image_hue":"0x4b5525","title":"瞎扯 · 如何正确地吐槽","url":"https://daily.zhihu.com/story/9731510","hint":"VOL.2563","ga_prefix":"010406","images":["https://pic4.zhimg.com/v2-e59b951ad15e86eb0beace6288237e16.jpg?source=8673f162"],"type":0,"id":9731510}
      ]
    
    */
    console.log( JSON.stringify(props.news.stories) );
    console.log(JSON.parse(JSON.stringify(props.news.stories)));
    // debugger
    console.log(two);
  }
};
</script>
<style lang="less">
.newsItem {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0.3rem 0;
  .con {
    margin-right: 0.3rem;
    color: #000;

    h4 {
      font-size: 0.32rem;
      font-weight: normal;
      line-height: 0.5rem;
      overflow: hidden;
    }

    span {
      display: block;
      color: #999;
      line-height: 0.5rem;
    }
  }
  .pic {
    width: 1.8rem;
    height: 1.5rem;
    background: #eee;
    img {
      display: block;
      width: 100%;
      height: 100%;
      border-radius: 0.1rem;
    }
  }
}
</style>