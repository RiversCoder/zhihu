<template>
  <header class="headerBox">
    <div class="title">
      <div class="time">
        <span>01日</span>
        <span>01月</span>
      </div>
      <h1>大喵知乎日报</h1>
    </div>
    <div class="pic">
      <img src="https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=2438864829,3057510527&fm=26&gp=0.jpg" alt />
    </div>
  </header>
</template>
<script>
export default {
  
};
</script>
<style lang="less">
.headerBox {
  position: fixed;
  top: 0;
  left: 0;
  z-index: 20;

  display: flex;
  justify-content: space-between;
  align-items: center;

  box-sizing: border-box;
  padding: 0 0.2rem;
  width: 100%;
  height: 1.2rem;
  background: #fff;

  .pic {
    width: 0.7rem;
    height: 0.7rem;
    background: url("../assets/images/timg.jpg") no-repeat;
    background-size: 100% 100%;
    border-radius: 50%;

    img {
      display: block;
      width: 100%;
      height: 100%;
      border-radius: 50%;
    }
  }

  .title {
    display: flex;
    justify-content: flex-start;
    align-items: center;

    .time {
      padding: 0 0.2rem;
      border-right: 0.02rem solid #eee;

      span {
        display: block;
        text-align: center;
        font-size: 0.24rem;
        &:nth-child(1) {
          font-size: 0.34rem;
          font-weight: bold;
        }
      }
    }

    h1 {
      padding: 0 0.2rem;
      font-size: 0.4rem;
    }
  }
}
</style>