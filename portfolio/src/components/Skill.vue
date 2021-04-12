<template>
<!-- skill -->
<section class="skill section" id="skill">
  <div class="inner">
    <h2 class="title">SKILL</h2>
    <div class="skill-list">
      <div class="skill-item">
        <p class="skill-img"><img src="@/assets/logo.png" alt=""></p>
        <div class="skill-body">
          <h3 class="skill-name">HTML5/CSS3</h3>
          <p class="skill-text">
            テキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入ります。</p>
        </div>
      </div>
      <div class="skill-item">
        <p class="skill-img"><img src="@/assets/logo.png" alt=""></p>
        <div class="skill-body">
          <h3 class="skill-name">WordPress</h3>
          <p class="skill-text">
            テキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入ります。</p>
        </div>
      </div>
      <div class="skill-item">
        <p class="skill-img"><img src="@/assets/logo.png" alt=""></p>
        <div class="skill-body">
          <h3 class="skill-name">JavaScript</h3>
          <p class="skill-text">
            テキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入ります。</p>
        </div>
      </div>
      <div class="skill-item">
        <p class="skill-img"><img src="@/assets/logo.png" alt=""></p>
        <div class="skill-body">
          <h3 class="skill-name">Photoshop</h3>
          <p class="skill-text">
            テキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入ります。</p>
        </div>
      </div>
      <div class="skill-item">
        <p class="skill-img"><img src="@/assets/logo.png" alt=""></p>
        <div class="skill-body">
          <h3 class="skill-name">Illustrator</h3>
          <p class="skill-text">
            テキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入ります。</p>
        </div>
      </div>
      <div class="skill-item">
        <p class="skill-img"><img src="@/assets/logo.png" alt=""></p>
        <div class="skill-body">
          <h3 class="skill-name">XD</h3>
          <p class="skill-text">
            テキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入りますテキストが入ります。</p>
        </div>
      </div>
    </div>
  </div>
</section>
<!-- /skill -->
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/*--------------------------------
Skill
---------------------------------*/
.skill-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin-bottom: -50px;
}
.skill-item {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  width: 48%;
  margin-bottom: 50px;
}
.skill-img {
  width: 60px;
  height: auto;
  margin-right: 20px;
}
.skill-body {
  flex: 1;
}
.skill-name {
  margin-bottom: 3px;
}
/*media Queries 767
--------------------------------------*/
@media screen and (max-width: 767px) {
  /* Skill */
  .skill-list {
    display: block;
    margin-bottom: 0;
  }
  .skill-item {
    width: 100%;
    margin-bottom: 35px;
  }
  .skill-item:last-child {
    margin-bottom: 0;
  }
}
</style>
