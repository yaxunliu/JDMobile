<!-- category -->
<template>
  <div class="category-waraper">
    <ul class="category-list">
      <li class="category-item"><a><img src="../../images/nav0.png"><div>优惠券</div></a></li>
      <li class="category-item"><a><img src="../../images/nav1.png"><div>9.9元拼</div></a></li>
      <li class="category-item"><a><img src="../../images/nav2.png"><div>找折扣</div></a></li>
      <li class="category-item"><a><img src="../../images/nav3.png"><div>唯品会</div></a></li>
      <li class="category-item"><a><img src="../../images/nav4.png"><div>京东超市</div></a></li>
      <li class="category-item"><a><img src="../../images/nav5.png"><div>挑礼物</div></a></li>
      <li class="category-item"><a><img src="../../images/nav6.png"><div>领金豆</div></a></li>
      <li class="category-item"><a><img src="../../images/nav7.png"><div>京东手机</div></a></li>
    </ul>
  </div>
</template>

<script>
  
  export default { }

</script>

<style scoped>

.category-waraper {
  width: 100%;
  max-width: 640px;
  min-width: 320px;
  margin: 0 auto;
  margin-top: 10px;

}

.category-list {
  width: 100%;
  list-style: none;
  overflow: auto;
}

.category-item {
  float: left;
  width: 25%;
  background-color: white;
  text-align: center;
  height: 84px;
}

.category-item img {
  width: 40px;
  height: 40px;
  margin-top: 15px;
}

</style>