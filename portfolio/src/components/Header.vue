<template>
<!-- header -->
<div class="header ">
  <div class="inner">
    <h1 class="header-logo">
      <a href=".">{{ name }}</a>
    </h1>
    <nav class="header-nav">
      <ul class="header-nav-list">
        <li class="header-nav-item"><a href="#about">ABOUT</a></li>
        <li class="header-nav-item"><a href="#skill">SKILL</a></li>
        <li class="header-nav-item"><a href="#works">WORKS</a></li>
      </ul>
    </nav>
  </div>
</div>
<!-- /header -->
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      name: 'MY PORTFOLIO'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/*--------------------------------
ヘッダー
---------------------------------*/
.header {
  position: fixed;
  top: 0;
  z-index: 1;
  width: 100%;
  height: 10vh;
  background-color: #d6e9ca;
  box-shadow: 0 5px 10px -6px rgba(0,0,0,.1);
}
.header .inner {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 20px 40px;
}
.header-logo {
  font-size: 20px;
  font-weight: bold;
  line-height: 1.2;
  margin-right: 20px;
  letter-spacing: .05em;
}
.header-logo a {
  color: #3a5b52;
}
.header-nav-list {
  display: flex;
  justify-content: space-between;
}
.header-nav-item:not(:last-child){
  margin-right: 20px;
}
.header-nav-item a {
  position: relative;
  font-size: 14px;
  font-weight: bold;
  display: inline-block;
  padding: 5px 0;
  transition: .3s;
  letter-spacing: .05em;
  color: #3a5b52;
}
.header-nav-item a::after {
  position: absolute;
  bottom: 0;
  left: 50%;
  width: 0;
  height: 2px;
  content: '';
  transition: .3s;
  -webkit-transform: translateX(-50%);
  transform: translateX(-50%);
  background-color: #54917f;
}
.header-nav-item a:hover::after {
  width: 100%;
}
/*media Queries 767
---------------------------------------*/
@media screen and (max-width: 767px) {
  /* ヘッダー */
  .header .inner {
    padding: 15px;
  }

  .header-logo {
    font-size: 15px;
    margin-right: 15px;
  }

  .header-nav-item:not(:last-child) {
    margin-right: 10px;
  }

  .header-nav-item a {
    font-size: 10px;
  }

  .header-nav-item a:after {
    display: none;
  }
}
</style>
