<!-- product -->
<template>
  <div class="product-waraper">
    <section class="product-section">
      <div class="product-header second-kill">
        <span class="time-icon">
          <img >
        </span>
        <span class="sk-title">掌上生活</span>
        <div class="time">
          <span>0</span>
          <span>0</span>
          <span>:</span>
          <span>0</span>
          <span>0</span>
          <span>:</span>
          <span>0</span>
          <span>0</span>
        </div>

        <span style="float: right; margin-right: 10px">更多&gt;</span>
      </div>
      <div class="product-content">
        <div class="product-sk-item">
          <a><img src="../../images/detail01.jpg" style="width: 60%;"></a>
          <p>¥10.00</p>
          <p>¥10.00</p>
        </div>
        <div class="product-sk-item">
          <a><img src="../../images/detail01.jpg" style="width: 60%"></a>
          <p>¥10.00</p>
          <p>¥10.00</p>
        </div>
        <div class="product-sk-item">
          <a><img src="../../images/detail01.jpg" style="width: 60%"></a>
          <p>¥10.00</p>
          <p>¥10.00</p>
        </div>
      </div>
      
    </section>

    <div class="section">
      <div class="product-header">京东商城</div>
      <div class="section-detail clearfix">
        <a class="border-bottom float-left w_50"><img src="../../images/cp4.jpg"></a>
        <a class="border-bottom float-left w_50"><img src="../../images/cp5.jpg"></a>
        <a class="border-left float-right w_50"><img src="../../images/cp6.jpg"></a>
      </div>
    </div>
    <div class="section">
      <div class="product-header">京东商城</div>
      <div class="section-detail clearfix">
        <a class="border-bottom float-left w_50"><img src="../../images/cp1.jpg"></a>
        <a class="border-bottom float-left w_50"><img src="../../images/cp5.jpg"></a>
        <a class="border-left float-right w_50"><img src="../../images/cp6.jpg"></a>
      </div>
    </div>
     <div class="section">
      <div class="product-header">京东商城</div>
      <div class="section-detail clearfix">
        <a class="border-bottom float-left w_50"><img src="../../images/cp4.jpg"></a>
        <a class="border-bottom float-left w_50"><img src="../../images/cp5.jpg"></a>
        <a class="border-left float-right w_50"><img src="../../images/cp6.jpg"></a>
      </div>
    </div>
    <div class="last-section">
      <div class="product-header">京东商城</div>
      <div class="section-detail clearfix">
        <a class="border-right float-left w_50"><img src="../../images/cp1.jpg" style="display:block"></a>
        <a class="border-bottom float-left w_50"><img src="../../images/cp2.jpg"></a>
        <a class="border-bottom float-right w_50"><img src="../../images/cp3.jpg"></a>
        <div style="clear:both;height: 0; line-height: 0; font-size: 0"></div>
      </div>
    </div>

  </div>
</template>

<script>

  export default {
    data () {
      return {};
    },
  }
</script>

<style scoped>

.product-waraper {
  max-width: 640px;
  min-width: 320px;
  width: 100%;
  margin: 0 auto;
  background-color: #f5f5f5
}

.product-header {
  margin-top: 2px;
  height: 40px;
  background-color: #fff;
  border-bottom: #000 solid 1px;
  line-height: 40px;
  font-size: 14px;
  position: relative;
  padding-left: 23px;
}

.second-kill {
    border-bottom: none;
    overflow: auto;
}

.product-header::before {
  content: '';
  width: 3px;
  height: 20px;
  background-color: red;
  position: absolute;
  left: 10px;
  top: 10px;
}

.product-content {
  width: 100%;
  height: 100%;
  display: inline-block;
}

.time-icon {

  width: 16px;
  height: 20px;
  float: left;
  margin-top: 9px;
  margin-left: 0px; 
  background: url('../../images/seckill-icon.png') no-repeat center / 16px 20px;
}

.sk-title {
  float: left;
  color: red;
  margin-left: 10px;
  margin-right: 5px;
}


.time span {
  float: left;
  background-color: #333;
  width: 15px;
  line-height: 20px;
  color: #ffffff;
  margin-left: 3px;
  text-align: center;
  height: 20px;
  margin-top: 10px;

}

.time span:nth-child(3n) {
  color: #333;
  background-color: white;
  width: 3px;
}


.clearfix::before,
.clearfix::after{
    content: "";
    display: block;
    visibility: hidden;
    height: 0;
    line-height: 0;
    clear: both;
}



.product-sk-item {
  width: 33.333333%;
  height: 100%;
  text-align: center;
  float: left;
  background-color: #fff;
  padding: 10px 0;
}

.product-sk-item a {
  border-right: red solid 1px;
  font-size: 0;
  width: 100%;
  height: 100%;
  display: block;
}

.product-sk-item:last-child a {
  border: none;
}

.product-content:last-child p:nth-child(3) {
  text-decoration: line-through;
}

.product-section {
  padding-bottom: 10px;
}

.section {
  padding-bottom: 10px;
}

.last-section {
  background-color: rgb(77, 77, 4);
}


/* 组合样式 */



.w_50 {
  width: 50%;
}
.w_50 img{
  width: 100%;
  display: block;
}

.border-right {
  border-right: #ddd solid 1px;
}

.border-left {
  border-left: #ddd solid 1px;
}

.border-bottom {
  border-bottom: #ddd solid 1px;
}

.float-left {
  float: left;
}

.float-right {
  float: right;
}

</style>