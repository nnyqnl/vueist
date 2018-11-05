<template>

  <div class="head">
    <div class="headname">
      haohaoxiaoshuche
    </div>
    <div class="login-info fr">
      欢迎您，{{msg}} &nbsp;&nbsp;|&nbsp;&nbsp; <span class="login-out"><i class="iconfont">&#xe607;</i><span @click="logout">退出</span></span>
    </div>
    <div class="clear"></div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  methods: {
    logout: function () {
      alert('aa')
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.head {
    background-color: rgba(250, 186, 121, 0.801);
}
.headname {
    color:#42b983;
    font-size: 40px;
}
h1, h2 {
  font-weight: normal;
}

a {
  color: #42b983;
}
</style>
