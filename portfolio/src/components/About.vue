<template>
<!-- about -->
<section class="about section" id="about">
  <div class="inner">
    <h2 class="title">ABOUT</h2>
    <div class="profile">
      <p class="profile-img">
        <img src="@/assets/logo.png" alt="">
      </p>
      <div class="profile-body">
        <p>
          テキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入ります。
        </p>
        <p>
          テキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入ります。
        </p>
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
}
.profile-body p:not(:last-child) {
  margin-bottom: 30px;
}
</style>
