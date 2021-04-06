<template>
  <div id="wrapper">
    <Header/>
  </div>
</template>

<script>
import Header from './components/Header'
import MV from './components/MainVisual'

export default {
  name: 'Wrapper',
  components: {
    Header,
    MV
  }
}
</script>

<style>
body {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  font-size: 14px;
  line-height: 1.8;
  letter-spacing: .8px;
  color: #333;
}
a {
  transition: opacity .3s;
  text-decoration: none;
  color: #1ca9e3;
}
img {
  max-width: 100%;
  height: auto;
  vertical-align: bottom;
  border-style: none;
}
ul,
li {
  list-style: none;
}
.pc-only {
  display: block;
}
.sp-only {
  display: none;
}
/*--------------------------------
レイアウト
---------------------------------*/
#wrapper {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  padding-top: 73px;
}
.section {
  padding: 90px 0;
}
.section:nth-of-type(odd) {
  background-color: #f7f7f7;
}
.inner {
  max-width: 1340px;
  margin: 0 auto;
  padding: 0 40px;
}
</style>
