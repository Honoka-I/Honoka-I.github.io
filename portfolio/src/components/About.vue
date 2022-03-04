<template>
<!-- about -->
<section class="about section" id="about">
  <div class="inner">
    <h2 class="title">ABOUT</h2>
    <div class="profile">
      <p class="profile-img">
        <img src="@/assets/about.jpg" alt="">
      </p>
      <div class="profile-body">
        <p>
          大学在学中から1年半のインターンを経て卒業後、新卒でWebサービス開発を担う会社に入社。コーダーとして開発経験を積んだ後、2018年から所属した会社ではJavascriptを使用する開発を経験。現在はWebデザインやUIデザインについて勉強中。
        </p>
        <p>
          今後は、使用者に寄り添ったユーザビリティの高いデザインを作ることが出来る仕事に携わっていきたい。<br>今までコーディングやフロントエンドの仕事を通してwebデザインの仕事と関わってきたが、デザイナーの方が使用者に寄り添ったデザインを議論するのを見て、デザイナーに転職したいという思いが強くなった。<br>デザイナーとしては未熟ではあるが、今までフロント側として培ってきたスキルを活かしつつ、貢献していきたい。
        </p>
        <a href="https://github.com/Honoka-I" target="_blank" rel="noopener"><img src="@/assets/ico_github.png" alt="github-icon">Github</a>
      </div>
    </div>
  </div>
</section>
<!-- /about -->
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/*--------------------------------
About
---------------------------------*/
.profile {
  display: flex;
  flex-wrap: wrap;
  max-width: 800px;
  margin: 0 auto;
}
.profile-img {
  width: 20%;
  margin-right: 30px;
  border-radius: 50%;
}
.profile-img img {
  border-radius: 50%;
}
.profile-body {
  flex: 1;
  text-align: left;
}
.profile-body a {
  color: #3a5b52;
}
.profile-body a:hover {
  opacity: .7 ;
}
.profile-body img {
  width: 30px;
  margin-right: 10px;
}
.profile-body p:not(:last-child) {
  margin-bottom: 30px;
}
/*media Queries 767
--------------------------------------*/
@media screen and (max-width: 767px) {
  /* About */
  .profile {
    display: block;
  }
  .profile-img {
    width: 150px;
    margin: 0 auto;
    margin-bottom: 25px;
  }
  .profile-body p:not(:last-child) {
    margin-bottom: 20px;
  }
  .profile-body a {
    display: block;
    width: 100px;
    margin: 0 auto;
  }
}
</style>
