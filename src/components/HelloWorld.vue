<template>
  <div class="hello">
    <!--数据绑定-->
    <vue-ueditor-wrap v-model="msg"></vue-ueditor-wrap>
    <div>{{msg}}</div>
  </div>
</template>

<script>
  import VueUeditorWrap from 'vue-ueditor-wrap' // 引入vue-ueditor-wrap
  export default {
    name: 'HelloWorld',
    components: {
      VueUeditorWrap	//注册组件
    },
    data () {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>

<style scoped>

</style>
