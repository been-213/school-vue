<template>
  <header>{{title}}</header>
</template>

<script>
export default {
  name: 'BulletTitle',
  props: ['title']
}
</script>

<style lang="less" scoped>
header {
  text-align: center;
  font-size: 1.5em;
  padding: 20px 0;
  border-bottom: 1px solid #cccccc;
  color: white;
  background: #409eff;
  border-top-right-radius: 100px;
  border-top-left-radius: 100px;
}
</style>
