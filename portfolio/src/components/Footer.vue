<template>
<!-- footer -->
<footer class="footer">
  <div class="copyright">&copy;{{name}}</div>
</footer>
<!-- /footer -->
</template>

<script>
export default {
  name: 'Footer',
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
footer
---------------------------------*/
.footer {
padding: 30px;
background-color: #333;
}
.copyright {
font-size: 10px;
text-align: center;
color: #797979;
}
</style>
