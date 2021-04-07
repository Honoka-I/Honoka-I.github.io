<template>
<!-- main-visual -->
<div class="main-visual">
  <div class="main-visual-inner">
    <p class="main-visual-title">{{ name }}</p>
    <p class="main-visual-subtitle">PORTFOLIO</p>
  </div>
</div>
<!-- /main-visual -->
</template>

<script>
export default {
  name: 'MainVisual',
  data () {
    return {
      name: 'HONOKA IWASE'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/*--------------------------------
メインビジュアル
---------------------------------*/
.main-visual {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 35vh;
  text-align: center;
}
.main-visual-inner {
  padding: 0 40px;
}
.main-visual-title {
  font-size: 60px;
  font-weight: bold;
  line-height: 1.2;
  margin-bottom: 5px;
  letter-spacing: .1em;
}
.main-visual-subtitle {
  font-size: 20px;
  font-weight: bold;
  line-height: 1;
  margin-bottom: 40px;
  letter-spacing: .08em;
}
</style>
