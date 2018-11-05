<template>

  <div>
    <common-head></common-head>
    <common-menu></common-menu>
  </div>
</template>

<script>
import commonHead from '../components/commonHead.vue'
import commonMenu from '../components/commonMenu.vue'
export default {
  name: 'HelloWorld',
  components: {
    commonHead, commonMenu
  },
  data () {
    return {
      msg: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

a {
  color: #42b983;
}
</style>
