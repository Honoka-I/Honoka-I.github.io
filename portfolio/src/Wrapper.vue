<template>
  <div id="wrapper">
    <Header/>
    <MainVisual/>
    <Works/>
    <Skill/>
    <About/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header'
import MainVisual from './components/MainVisual'
import Works from './components/Works'
import Skill from './components/Skill'
import About from './components/About'
import Footer from './components/Footer'

export default {
  name: 'Wrapper',
  components: {
    Header,
    MainVisual,
    Works,
    Skill,
    About,
    Footer
  }
}
</script>

<style>
body {
  margin: 0;
  padding: 0;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  font-size: 14px;
  line-height: 1.8;
  letter-spacing: .8px;
  color: #333;
}
a {
  transition: opacity .3s;
  text-decoration: none;
  color: #ccc;
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
  color: #3a5b52;
  margin-top: 60px;
  padding-top: 73px;
}
.section {
  padding: 90px 0;
}
.section:nth-of-type(odd) {
  background-color: #fafafa;
}
.inner {
  max-width: 1340px;
  margin: 0 auto;
  padding: 0 40px;
}
/*--------------------------------
見出し
---------------------------------*/
.title {
  font-size: 34px;
  font-weight: bold;
  line-height: 1;
  margin-bottom: 40px;
  text-align: center;
  letter-spacing: .05em;
  color: #3a5b52;
}
.lead {
  margin-bottom: 30px;
}
/*media Queries 767
--------------------------------------*/
@media screen and (max-width: 767px) {
  body {
    margin: 0;
    font-size: 13px;
    line-height: 1.7;
  }
  .pc-only {
    display: none;
  }
  .sp-only {
    display: block;
  }
  /* 見出し */
  .title {
    font-size: 26px;
    margin-bottom: 20px;
  }
  /* レイアウト */
  .wrapper {
    padding-top: 57px;
  }
  .section {
    padding: 60px 0;
  }
  .inner {
    padding: 0 20px;
  }
}
</style>
