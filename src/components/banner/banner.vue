<!-- banner -->
<template>
  <div class="jd_banner">
    <ul class="banner-warapper">
      <li class="banner-item"><a><img src="../../images/l8.jpg"></a></li>
      <li class="banner-item"><a><img src="../../images/l1.jpg"></a></li>
      <li class="banner-item"><a><img src="../../images/l2.jpg"></a></li>
      <li class="banner-item"><a><img src="../../images/l3.jpg"></a></li>
      <li class="banner-item"><a><img src="../../images/l4.jpg"></a></li>
      <li class="banner-item"><a><img src="../../images/l5.jpg"></a></li>
      <li class="banner-item"><a><img src="../../images/l6.jpg"></a></li>
      <li class="banner-item"><a><img src="../../images/l7.jpg"></a></li>
      <li class="banner-item"><a><img src="../../images/l8.jpg"></a></li>
      <li class="banner-item"><a><img src="../../images/l1.jpg"></a></li>
    </ul>
    <ul class="pageControl">
      <li class="pageControl-item selectPage"></li>
      <li class="pageControl-item"></li>
      <li class="pageControl-item"></li>
      <li class="pageControl-item"></li>
      <li class="pageControl-item"></li>
      <li class="pageControl-item"></li>
      <li class="pageControl-item"></li>
      <li class="pageControl-item"></li>
    </ul>

  </div>
</template>

<script>

export default { }

</script>

<style scoped>

.jd_banner {
  width: 100%;
  overflow: hidden;
  position: relative;
  min-width: 320px;
  max-width: 640px;
  margin: 0 auto;
}

.banner-warapper {
  width: 1000%;
  list-style: none;
  transform: translateX(-10%);
}

.banner-item {
  width: 10%;
  float: left;
}

.banner-item img {
  display: block;
  width: 100%;

}

.pageControl {
  position: absolute;
  bottom: 6px;
  left: 50%;
  width: 118px;
  height: 6px;
  margin-left: -59px;
  list-style: none;
}

.pageControl-item {
  width: 6px;
  height: 6px;
  border-radius: 3px;
  margin-left: 10px;
  float: left;
  background-color: white;
}

.pageControl-item:first-child {
  margin-left: 0;
}

.selectPage {
    background-color: black;
}

</style>