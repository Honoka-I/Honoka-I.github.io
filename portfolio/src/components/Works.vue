<template>
<!-- works -->
<section class="works section" id="works">
  <div class="inner">
    <h2 class="title">WORKS</h2>
    <div class="works-list">
      <a class="works-item" href="https://www.cosme.net/html/spc/about-micael/" target="_blank" rel="noopener">
        <p class="works-img"><img  src="@/assets/works_1.png" alt="" /></p>
        <p class="works-name">キャラクター紹介ページ作成</p>
        <p class="works-info">Coding(PC/SP)</p>
      </a>
      <a class="works-item" href="https://s.cosme.net/tags/item/item_id/1006/top/" target="_blank" rel="noopener">
        <p class="works-img"><img src="@/assets/works_2.png" alt="" /></p>
        <p class="works-name">カテゴリタグページのトップ改修</p>
        <p class="works-info">Coding(SP)</p>
      </a>
      <a class="works-item" href="https://www.cosme.net/bestcosme/archive/2019_half/" target="_blank" rel="noopener">
        <p class="works-img"><img src="@/assets/works_3.png" alt="" /></p>
        <p class="works-name">イベントページ作成</p>
        <p class="works-info">Coding(PC/SP)</p>
      </a>
      <a class="works-item" href="https://career.cosme.net/" target="_blank" rel="noopener">
        <p class="works-img"><img src="@/assets/works_4.png" alt="" /></p>
        <p class="works-name">トップページ改修</p>
        <p class="works-info">Coding(Responsive)</p>
      </a>
      <a class="works-item" href="https://gourmet.epark.jp/" target="_blank" rel="noopener">
        <p class="works-img"><img src="@/assets/works_5.png" alt="" /></p>
        <p class="works-name">トップページ,検索結果改修</p>
        <p class="works-info">Coding(Responsive)</p>
      </a>
      <a class="works-item" href="http://www.honkei.jp/" target="_blank" rel="noopener">
        <p class="works-img"><img src="@/assets/works_6.png" alt="" /></p>
        <p class="works-name">サイト改修</p>
        <p class="works-info">Design,Coding(PC)</p>
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
  color: #3a5b52;
}
.works-item:hover {
  opacity: .7;
}
.works-item:nth-of-type(3n) {
  margin-right: 0;
}
.works-img img {
  width: 100%;
  height: 240px;
  object-fit: contain;
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
/*media Queries 767
--------------------------------------*/
@media screen and (max-width: 767px) {
  /* Works */
  .works-name {
    font-size: 10px;
  }
  .works-list {
    justify-content: space-between;
  }
  .works-item {
    flex: 0 0 48%;
    margin-right: 0;
    margin-bottom: 30px;
  }
  .works-img img {
    height: 130px;
  }
}
</style>
