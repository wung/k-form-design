<template>
  <header v-text="title"></header>
</template>
<script>
/*
 * athor kcz
 * date 2019-11-20
 */
export default {
  props: {
    title: {
      type: String,
      default: "表单设计器 --by kcz"
    }
  }
};
</script>
<style lang="less" scoped>
header {
  width: 100%;
  height: 60px;
  line-height: 60px;
  text-align: center;
  background: #54c7f6;
  color: #fff;
  font-size: 18px;
  font-weight: bold;
}
</style>
