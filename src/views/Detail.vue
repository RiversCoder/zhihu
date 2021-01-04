<template>
  <div class="detailBox">
    <!-- <div class="headBox">
      <span class="back" @click="$router.push('/')">返回</span>
      <img :src="image" alt />
      <div class="info">
        <h3>{{title}}</h3>
        <span>{{ section }}</span>
      </div>
    </div>
    <div class="content" v-html="body"></div> -->
    <div class="headBox">
      <span class="back" @click="$router.push('/')">返回</span>
      <img src="https://pic2.zhimg.com/v2-ef49f243658edb316fd306be39e2f9be.jpg?source=8673f162" alt />
      <div class="info">
        <h3>野生动物吃鱼不会被刺卡住吗？</h3>
        <span>奇怪的知识</span>
      </div>
    </div>
    <div class="content" >
      <div class="main-wrap content-wrap">
      <div class="headline">

      <div class="img-place-holder"></div>



      </div>

      <div class="content-inner">




      <div class="question">
      <h2 class="question-title"></h2>

      <div class="answer">

      <div class="meta">
      <img class="avatar" src="https://pic1.zhimg.com/v2-a828256341663bc1234f028f047f576d_l.jpg?source=8673f162">
      <span class="author">苏澄宇，</span><span class="bio">动物科学 / 动物营养 / 冷门问题收割者</span>
      <a href="https://www.zhihu.com/question/276893458/answer/1639198046" class="originUrl" hidden="">查看知乎原文</a>
      </div>

      <div class="content">
      <p>不是所有动物都有高超的吃鱼技巧，所以会有野生动物被鱼刺卡喉，而且一卡住基本都活不长了。</p>
      <p>比如下面这条海狗……</p>
      <hr><p>在澳大利亚东南部的康兰角（Cape Conran），有人在那发现了一直躺在沙滩上的新澳海狗（Arctocephalus forsteri）。走近一看，才发现已经死了，瘦骨嶙峋的，而且它的脸上扎了根大鱼刺……</p>
      <figure><img class="content-image" src="https://pic1.zhimg.com/v2-a1774680c542ad432645cb830261feff_720w.jpg?source=8673f162" alt=""><figcaption>图片来源：文献 1</figcaption></figure><p>这里简单介绍一下新澳海狗，它是海狮科的一员。主要分布在亚南极岛上，比如澳大利亚、新西兰南岛、奥克兰等。和真海狮相比，新澳海狗的毛明显比海狮短了不少，这是外表上明显的区别。</p>
      <figure><img class="content-image" src="https://pic1.zhimg.com/v2-4f5d6249c30dcb1048f91f11b8e2c827_720w.jpg?source=8673f162" alt=""><figcaption>新澳海狗 图源：wikipedia</figcaption></figure><p>如果换做《走近科学》，关于海狗的死亡真相应该可以讲上两期。这里就一篇文章解决吧。</p>
      <p>DELWP（环境、土地、水资源规划部）、维多利亚博物馆和蒙纳士大学的一组科学家，决定对调查海狗的死亡真相。他们给海狗做了尸检，对海狗的头部进行了 CT 扫描<sup>[1]</sup>。</p>
      <p>结果是惊人的：<strong>鱼刺不仅刺穿了海狗的脸颊，还刺穿了鼻子和下巴。</strong></p>
      <p>在进一步的检查中，科学家发现伤口不是两三处，而是 10 处刺伤，有些可能是鱼刺被拔出之后，造成的二次创伤。伤口遍布脸部和喉咙，有一些看起来已经溃烂。</p>
      <figure><img class="content-image" src="https://pic2.zhimg.com/v2-43e49f3c4b0a86d7aa28d16ee643d585_720w.jpg?source=8673f162" alt=""><figcaption>计算机模拟出了鱼刺的位置。红色物体是鱼刺，总共被 6 根鱼刺刺伤。下面标记的是每处刺伤的鱼骨。图源：文献 1</figcaption></figure><p>这些伤口导致海狗无法进食，最终导致海狗被饿死。</p>
      <hr><p><strong>谁是杀死海狗的真凶？</strong></p>
      <p>为了对抗捕食者，许多鱼类已经进化出了复杂的防御系统来对抗捕食者。</p>
      <p>就比如，可以给捕食者造成痛苦的毒刺。</p>
      <p>在前面的那副 CT 图中，你应该注意到刺伤海狗的刺不止一种，如果你仔细观察的的话，会发现是 2 种不同的鱼的鱼刺造成的。</p>
      <p>一种是神出鬼没的锄吻银鲛，它是鲨鱼的远房亲戚，嘴巴像锄头一样。这是一种长相奇特的鱼，有人觉得鱼头前面多出来的那一部分像象鼻子，所以又叫它 elephant fish。</p>
      <figure><img class="content-image" src="https://pic2.zhimg.com/v2-1f171fcca26ec3ebeb2338e3d4b6f5e4_720w.jpg?source=8673f162" alt=""><figcaption>图源：Wikipedia</figcaption></figure><figure><img class="content-image" src="https://pic1.zhimg.com/v2-c861791dad7d9cbaae735f4ba1511a42_720w.jpg?source=8673f162" alt=""><figcaption>图源：Australian Museum</figcaption></figure><p>造成刺伤的，正是锄吻银鲛的背鳍上的鱼刺。（1、2 的鱼刺）</p>
      <figure><img class="content-image" src="https://pic4.zhimg.com/v2-c8143d73181d37bae5b05eaf26a93249_720w.jpg?source=8673f162" alt=""><figcaption>图源：文献 1</figcaption></figure><p>另一个则是少斑扁魟（hong），这是一种带有带毒尾棘的鱼，可以像蝎子一样自由摆动。</p>
      <figure><img class="content-image" src="https://pic1.zhimg.com/v2-1571212fb52f5bfc5e50da5935889c24_720w.jpg?source=8673f162" alt=""><figcaption>图源：reef life survey</figcaption></figure><figure><img class="content-image" src="https://pic1.zhimg.com/v2-b67cdb76b89aefa445e88b8186684e0a_720w.jpg?source=8673f162" alt=""><figcaption>图源：fish of Australia</figcaption></figure><p>它的尾棘就像蜜蜂的螫针，可以对潜在的捕食者造成致伤甚至致命的威胁。有人就被它刺死过，大名鼎鼎的 Discovery 探索节目主持人史蒂夫.厄文，在节目录制下水过程中就被一条扁魟刺中胸部，最后死亡。（3、4、5、6 的鱼刺）</p>
      <figure><img class="content-image" src="https://pic4.zhimg.com/v2-0afc6a4b5054e2d41547a118a120e7e7_720w.jpg?source=8673f162" alt=""><figcaption>少斑扁魟标本 图源：文献 1</figcaption></figure><p>大部分人中招通常是在浅海涉水时，不小心踩到它才受伤的，尾棘刺进人的足或腿部释放毒液。根据默沙东诊疗指南，被扁魟刺伤后，常见的症状有晕厥、乏力、恶心和焦虑。少见的症状有呕吐、腹泻、出汗、全身痉挛、呼吸困难和死亡<sup>[2]</sup>。</p>
      <figure><img class="content-image" src="https://pic2.zhimg.com/v2-820a8015481cc2b2f342e161017fa405_720w.jpg?source=8673f162" alt=""><figcaption>刺中海狗脸部，长满了倒勾的扁魟尾刺 图源：文献 1</figcaption></figure><p>这两种鱼有一个共同点，都是软骨鱼。所谓的软骨鱼，如字面意思，它们的骨架是由软骨构成。不要被软骨两个字欺骗了，以为它们全部的骨头都是软趴趴的，其实脊椎还是部分骨化的，这也就意味着身体的一部分还是挺硬的，不然怎么会把会刺死一只海狗呢？</p>
      <hr><p><strong>海狗平常都吃些啥？没事就会吃这么危险的鱼吗？</strong></p>
      <p>想要知道一种动物的食物列表，一般有两种办法，一种办法直接观察它在饭点的时候找了什么吃的，另一种办法就是从找它的粪便，看它屎里有什么动物的 DNA。</p>
      <p>而科学家对新澳海狗的研究方法正是第二种，这种方法明显更简单方便些，毕竟不用天天追着海狗下海上陆，那可得多累，而且观察到的不一定全面。只要从沙滩上弄些屎，带回实验室里做分析就能知道结果，这不简单了许多。</p>
      <p>通过对海狗的粪便 DNA 分析，科学家发现新澳海狗主要以锄吻银鲛为食<sup>[3]</sup>，也就是前面刺死海狗的那种鱼。虽然扁魟和其他鳐鱼并不多，但起码也是日常饮食的一部分。那么问题来了，为啥这么多海狗平常吃这些危险的鱼都没事，这只死在海滩上的海狗就倒霉了呢？</p>
      <p>要弄清楚这点，我们得先清楚海狗平常是如何处理这些鱼刺的。</p>
      <p>对于海狗来说，平常吃些小鱼小虾的，都可以快速地一口一个给吃掉。但遇到稍微大一点的鱼，就不能一口闷了，而是先得分成好几块来吃。面对锄吻银鲛和扁魟这类大家伙的时候，海狗会用嘴咬住一端，然后猛烈地摇晃猎物，来达到分成小块的目的。毕竟没有手来撕开，全都得嘴巴来解决了。</p>
      <figure><img class="content-image" src="https://pic1.zhimg.com/v2-01244f110b7d8148763a6e1291100563_720w.jpg?source=8673f162" alt=""><figcaption>海狗在撕开锄吻银鲛的时候，会避开背后的利刺。图源：Vincent Antony</figcaption></figure><figure><img class="content-image" src="https://pic1.zhimg.com/v2-07e39d0051a28c754d7cccf18a162723_720w.jpg?source=8673f162" alt=""><figcaption>海狗在撕开锄吻银鲛的时候，会避开背后的利刺。图源：Vincent Antony</figcaption></figure><p>一般来说，海狗都会以正确的姿势杀死并吃掉一条鱼。尽管如此，这种操作还是有风险的，风险的因素可能来源于猎物的挣扎，可能是技术不到位，也有可能纯粹是运气不好。吃鱼的方式一旦出现问题，轻则受伤，重则就是那头躺在沙滩上的死海狗了。</p>
      <p>回到死亡的那只海狗。通过对海狗的伤口调查，科学家推测可能是这只海狗在试图撕开猎物的时候，不小心被锄吻银鲛扇了一巴掌，然后刺穿了脸颊。</p>
      <hr><p><strong>不只是人类，在面对鱼刺的时候，动物也会很苦恼</strong></p>
      <p>其实不止是海狗，其他动物在吃鱼的时候，也会面临被鱼刺给伤着的风险。哪怕是大鱼吃小鱼的时候……</p>
      <p>2017 年的一项研究中，科学家对一条及达尖犁头鳐（<em>Rhynchobatus djiddensis）</em>的进行研究<sup>[4]</sup>。发现它的嘴里插了一根很明显的鱼刺。</p>
      <figure><img class="content-image" src="https://pic4.zhimg.com/v2-01e690319fce962c4787a05fffabdcfd_720w.jpg?source=8673f162" alt=""><figcaption>图中圈出来的地方是一根鱼刺（忍不住吐槽，鳐鱼的脸总有些滑稽） 图源：文献 4</figcaption></figure><p>在进一步的 CT 扫描之后，发现它的嘴里远不止一根刺，那些细小的刺扎满了整个嘴，细数下来，共有 62 根鱼刺，并且大部分都是来自扁魟的。虽然鳐鱼没有因为鱼刺而死，但看着都觉得很疼。（扁魟可真危险……</p>
      <figure><img class="content-image" src="https://pic1.zhimg.com/v2-32bdb72b079ff46a04fe18bef7b25578_720w.jpg?source=8673f162" alt=""><figcaption>红色的是刺 图源：文献 4</figcaption></figure><p>看来鱼刺不止困扰了人类，还困扰了其他动物，而且一不小心还有被鱼刺弄死的风险。但如果把鱼和风险摆在动物面前，动物还是会毫不犹豫地去选择食物，毕竟吃鱼可能会受伤，甚至会死，但不吃鱼真的会死。</p>
      <p><strong>出品：科普中国</strong></p>
      <p><strong>制作</strong>：<strong>苏澄宇</strong></p>
      <p><strong>监制：中国科学院计算机网络信息中心</strong></p>
      <figure><img class="content-image" src="https://pic2.zhimg.com/v2-4fe7f37db2fd41c04e067b468acd8d9b_720w.jpg?source=8673f162" alt=""></figure>
      </div>
      </div>


      <div class="view-more"><a href="https://www.zhihu.com/question/276893458">查看知乎讨论<span class="js-question-holder"></span></a></div>

      </div>


      </div>
      </div>  
    </div>
  </div>
</template>
<script>
import { watch, toRefs,ref,reactive } from "vue";
import API from "../api";
export default {
  setup() {
    let id = ref(0);
    let state = reactive({
      image: '',
      body: '',
      title: '',
      section: ''
    });
    watch(id, async () => {
      let { image, body, title,section } = await API.zhihu.API_DETAIL(id.value)
      state.image = image
      state.body = body
      state.title = title,
      state.section = section? section.name : '佚名'
    });
    return {
      id,
      ...toRefs(state)
    }
  },
  beforeMount(){
    let { id } = this.$route.params
    this.id = id
    
  }
};
</script>
<style lang="less" scoped>
.detailBox {
  .headBox {
    position: relative;
    height: 7.5rem;
    overflow: hidden;
    .back{
      position: absolute;
      left: .3rem;
      top: .3rem;
      color: #fff;
    }
    img {
      display: block;
      width: 100%;
      height: 100%;
    }

    .info {
      position: absolute;
      left: 0;
      bottom: 0;
      box-sizing: border-box;
      padding: 0.2rem;
      width: 100%;
      background: linear-gradient(
        0,
        rgba(55, 86, 103, 0.5),
        rgba(55, 86, 103, 0)
      );
      color: #fff;
      line-height: 0.6rem;

      h3 {
        font-size: 0.38rem;
      }

      span {
        display: block;
        font-size: 0.28rem;
        text-align: right;
      }
    }
  }
}
</style>