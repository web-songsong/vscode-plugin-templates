<template>
  <div class="{{fileName}}">
    .vue文件 可以获取写入变量fileName: {{fileName}}
    模板中自定义变量 {{{message}}}
  </div>
</template>
<script>
export default {
  data() {
    return {
      message: 'hellow word'
    }
  },
}
</script>
<style lang="less" scoped>
.{{fileName}} {
}
</style>
