<template>
  <div class="topNav">
    <div class="topleft">
      <svg class="icon" aria-hidden="true">
        <use xlink:href="#icon-danlieliebiao"></use>
      </svg>
    </div>

    <div class="topContent">
      <span @click="$router.push('/infoUser')">我的</span>
      <span class="active">发现</span>
      <span>云村</span>
      <span>视频</span>
    </div>

    <div class="topRight">
      <svg class="icon" aria-hidden="true" @click="$router.push('/search')">
        <use xlink:href="#icon-sousuo"></use>
      </svg>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="less" scoped>
.topNav {
  display: flex;
  width: 100%;
  height: 1rem;
  padding: 0.2rem;
  justify-content: space-between;
  align-items: center;
  .topContent {
    display: flex;
    width: 65%;
    height: 100%;
    justify-content: space-around;
    font-size: 18px;
    .active{
      font-weight: 900;
    }
  }
}
</style>