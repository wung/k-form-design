<template>
  <div>
    <k-form-design @save="handleSave" showClose @close="handleClose" />
  </div>
</template>
<script>
/*
 * athor kcz
 * date 2019-11-20
 */
export default {
  methods: {
    handleSave(jsonData) {
      console.log(jsonData);
      this.$message.success("触发保存方法");
    },
    handleClose() {
      this.$message.success("触发关闭方法");
    }
  }
};
</script>
