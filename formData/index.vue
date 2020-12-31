<template>
  <div class="{{fileNmae}}">
    这是用户定义的filename : {{fileNmae}}
    这是组件内部的数据: \{{message}}
  </div>
</template>
<script>
export default {
  data() {
    return {
      message: 'this template message'
    }
  },
 }
</script>
<style lang="less" scoped>
.{{fileNmae}}{
}
</style>
