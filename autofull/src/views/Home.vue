<template>
  <div class="home">
    <div class="header">
      <div class="left"><img src="../assets/img/nav.png" alt="" /></div>
      <div class="center"><img src="../assets/img/logo.png" alt="" /></div>
      <div class="right"><img src="../assets/img/search.png" alt="" /></div>
    </div>
    <mt-swipe class="banner" :auto="4000">
      <mt-swipe-item
        ><img src="../assets/img/banner1.jpg" alt=""
      /></mt-swipe-item>
      <mt-swipe-item
        ><img src="../assets/img/banner2.jpg" alt=""
      /></mt-swipe-item>
      <mt-swipe-item
        ><img src="../assets/img/banner3.jpg" alt=""
      /></mt-swipe-item>
      <mt-swipe-item
        ><img src="../assets/img/banner4.jpg" alt=""
      /></mt-swipe-item>
      <mt-swipe-item
        ><img src="../assets/img/banner5.jpg" alt=""
      /></mt-swipe-item>
    </mt-swipe>
    <div class="container">
      <div class="product">
        <div class="title">
          <img src="../assets/img/product1.png" alt="" />
        </div>
        <div class="product_list">
          <div class="top">
            <a href=""><img src="../assets/img/1.jpg" alt="" /></a>
            <a href=""><img src="../assets/img/2.jpg" alt="" /></a>
          </div>
          <div class="top">
            <a href=""><img src="../assets/img/3.jpg" alt="" /></a>
            <a href=""><img src="../assets/img/4.jpg" alt="" /></a>
          </div>
        </div>
      </div>
      <div class="more">
        <a href=""> 查看更多</a>
      </div>
      <div class="news">
        <img src="../assets/img/news1.png" alt="" />
      </div>
      <div class="img">
        <a href=""
          ><img src="../assets/img/news1.jpg" alt="" />
          <p class="mask">
            <span>AutoFull傲风赞助LOL王牌对抗赛，见证斗鱼最强战队诞生！</span>
            <i>→</i>
          </p></a
        >
        <a href=""
          ><img src="../assets/img/news2.jpg" alt="" />
          <p class="mask">
            <span>恭喜傲风军团天霸战队夺得PCS东亚慈善赛冠军！</span>
            <i>→</i>
          </p></a
        >
        <a href=""
          ><img src="../assets/img/news3.jpg" alt="" />
          <p class="mask">
            <span>AutoFull傲风助力WUCL，见证全球高校生一起酣战！ </span>
            <i>→</i>
          </p></a
        >
      </div>
      <div class="more">
        <a href=""> 查看更多</a>
      </div>
      <div class="news">
        <img src="../assets/img/partner1.png" alt="" />
      </div>
      <div class="footer">
        <ul>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.home .header {
  background: url("../assets/img/nav-bg.jpg") center/cover;
  display: flex;
  justify-content: space-between;
  padding: 3%;
}
.home .header .left img {
  width: 30px;
}
.home .header .center img {
  width: 180px;
}
.home .header .right img {
  width: 30px;
}

.home .banner {
  height: 250px;
}
.home .banner img {
  width: 100%;
  height: 100%;
}
.home .mint-swipe-indicator {
  background-color: #fff;
  opacity: 1;
}
.home .is-active {
  background: rgb(255, 0, 0) !important;
}
.home .container {
  background-color: #222;
}
.home .product .title {
  text-align: center;
  padding: 18px 0 11px;
}
.home .product .title img,
.home .news img {
  width: 110px;
}
.home .product_list .top {
  display: flex;
  justify-content: space-between;
}
.home .product_list .top a {
  padding: 3px;
}
.home .product_list img {
  width: 100%;
}
.home .more {
  text-align: center;
  margin: 0 0 15px;
  padding: 6% 0;
}
.home .more a {
  padding: 6px 12px;
  background: linear-gradient(#ff4344, #c00101);
  color: #fff;
  display: inline-block;
  text-decoration: none;
  border-radius: 5px;
  font-size: 12px;
}
.home .news {
  text-align: center;
  padding: 0 0 4% 0;
}
.home .img {
}

.home .img a {
  display: block;
  margin-bottom: 15px;
  position: relative;
}
.home .img img {
  width: 100%;
}
.home .img .mask {
  position: absolute;
  bottom: 0;
  background-color: rgba(0, 0, 0, 0.6);
  line-height: 35px;
  width: 100%;
  display: flex;
  justify-content: space-between;
}

.home .mask span {
  color: #fff;
  font-size: 14px;
  width: 80%;
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
  line-height: 35px;
  float: left;
  padding-left: 10px;
}
.home .mask i {
  color: #fff;
  float: right;
  width: 10%;
}
</style>