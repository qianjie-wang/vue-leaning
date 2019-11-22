<template>
  <div class="logo">
      <div id="top">
        <img src="https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo_top_86d58ae1.png">
      </div>
      <ul id="header">
        <a href=#><li>首页</li></a>
        <li><a>关于我们</a></li>
        <li><a>经营范围</a></li>
        <li><a>新闻动态</a></li>
        <li><a>联系我们</a></li>
      </ul>
  </div>
</template>

<script>
export default {
  name: "Logo",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#top {
  float: left;
  border: solid;
}
ul {
  list-style-type: none;
  margin-left: 5%;
  margin-right: 10%;
  padding: 0;
}
li {
  float: right;
  margin: 0 10px 0 10px;
  font-size: 1.5em;
}
a {
  color: #42b983;
}
</style>
