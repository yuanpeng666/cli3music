<template>
  <div v-if="info"
       class="info">未找到与"{{keywords}}"相关的内容</div>
</template>

<script>
export default {
  name: '',
  props: {
    info: {
      type: Boolean,
      default: false
    },
    keywords: {
      type: String
    }
  }
}
</script>

<style lang='less' scoped>
.info {
  text-align: center;
  line-height: 1rem;
}
</style>
