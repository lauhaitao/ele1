<template>
    <div>
         <div class="search">
      <span class="sp1">
        <router-link to="/points">

    <img src="../../../static/img/右.png" alt="" >
    </router-link>
    </span>
  <span class="sp2">积分说明</span>
</div>
        <h3>Q1: 怎么获得积分？</h3>
        <p>在线支付的订单将获得订单积分奖励：</p>
        <h3>Q2: 积分用来做什么？</h3>
        <p>可以在积分商城兑换各种礼品。</p>
        <h3>Q3: 礼品兑换很多天了还没有收到，该怎么办？</h3>
<p>礼品从兑换日起，3个工作日（周末不算）内处理发货，发货后，通常会在3个工作日左右送达。</p>
<p>不会，手机充值卡兑换，是直接充值到您填写的手机号上，充值之前不会和您电话确认，所以您在填写电话的时候，请确认电话是否正确。</p>

<h3>Q4: 礼品兑换中的手机充值卡兑换，怎么样进行充值，充值之前会和我电话确认嘛？</h3>
    </div>
</template>

<script>
export default {
name:"sm"
}
</script>

<style scoped>
.search {
  height: 0.46rem;
  line-height: 0.46rem;
  color: white;
  background-color: #3190e8;
  position: relative;
  margin-bottom: 0.1rem;
}
.sp1 img {
  margin-top: 0.05rem;
}
.sp2 {
  position: absolute;
  right: 50%;
  top: 0;
  font-size: 0.19rem;
  font-weight: 700;
}
</style>
