<!-- header 组件 -->
<template>
  <div class="search-header">
      <div class="search-contains"> 
        <a class="search-logo"></a>
        <form action="#" class="search-form">
          <span class="search-icon"></span>
          <input type="search" class="search-input" placeholder="搜一搜:美味蛋糕">  
        </form>
        <a class="search-login">登录</a>
      </div>
    </div>
</template>

<script>
  export default {}
</script>

<style scoped>

.search-header {
  width: 100%;
  height: 44px;
  position: fixed;
  top: 0;
  left: 0;
  z-index: 1000;
}

.search-contains {
  max-width: 640px;
  min-width: 320px;
  margin: 0 auto;
  height: 100%;
  position: relative;
}

.search-logo {
  position: absolute;
  left: 10px;
  top: 4px;
  width: 60px;
  height: 36px;
  text-align: center;
  background: url('../../images/sprites.png') no-repeat 0 -103px / 200px 200px;
}

.search-form {
  width: 100%;
  height: 44px;
  padding-left: 70px;
  padding-right: 50px;
  position: relative;
}

.search-icon {
  position: absolute;
  width: 22px;
  height: 22px;
  left: 80px;
  top: 11px;
  background: url('../../images/sprites.png') no-repeat -60px -109px / 200px 200px;

}

.search-input {
  width: 100%;
  height: 34px;
  margin-top: 5px;
  border-radius: 17px;
  border: none;
  padding-left: 40px;
  padding-right: 20px;
}

.search-login {
  position: absolute;
  right: 0;
  top: 0;
  width: 50px;
  height: 44px;
  line-height: 44px;
  text-align: center;
  color: white;
}

</style>