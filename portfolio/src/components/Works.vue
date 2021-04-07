<template>
<!-- works -->
<section class="works section" id="works">
  <div class="inner">
    <h2 class="title">WORKS</h2>
    <div class="works-list">
      <a class="works-item" href="">
        <p class="works-img"><img  src="@/assets/logo.png" alt="" /></p>
        <p class="works-name">作品名が入る</p>
        <p class="works-info">Design / Coding(Responsive)</p>
      </a>
      <a class="works-item" href="">
        <p class="works-img"><img src="@/assets/logo.png" alt="" /></p>
        <p class="works-name">作品名が入る</p>
        <p class="works-info">Design / Coding(Responsive) / WordPress</p>
      </a>
      <a class="works-item" href="">
        <p class="works-img"><img src="@/assets/logo.png" alt="" /></p>
        <p class="works-name">作品名が入る</p>
        <p class="works-info">Design</p>
      </a>
      <a class="works-item" href="">
        <p class="works-img"><img src="@/assets/logo.png" alt="" /></p>
        <p class="works-name">作品名が入る</p>
        <p class="works-info">Banner Design</p>
      </a>
      <a class="works-item" href="">
        <p class="works-img"><img src="@/assets/logo.png" alt="" /></p>
        <p class="works-name">作品名が入る</p>
        <p class="works-info">Banner Design</p>
      </a>
      <a class="works-item" href="">
        <p class="works-img"><img src="@/assets/logo.png" alt="" /></p>
        <p class="works-name">作品名が入る</p>
        <p class="works-info">Banner Design</p>
      </a>
    </div>
  </div>
</section>
<!-- /works -->
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/*--------------------------------
Works
---------------------------------*/
.works-list {
  display: flex;
  flex-wrap: wrap;
  margin-bottom: -40px;
}
.works-item {
  width: 31.74603%;
  margin-right: 1.58730%;
  margin-bottom: 40px;
  color: #333;
}
.works-item:hover {
  opacity: .9;
}
.works-item:nth-of-type(3n) {
  margin-right: 0;
}
.works-imgimg {
  border: 1px solid #e6e6e6;
}
.works-name {
  font-size: 12px;
  font-weight: bold;
  margin-top: 8px;
}
.works-info {
  font-size: 10px;
}
</style>
