<template>
  <el-dialog
    title="Tips"
    :visible.sync="dialogVisible"
    width="30%"
    :before-close="handleClose"
  >
    <span>This is a message</span>
    <span slot="footer" class="dialog-footer">
      <el-button @click="dialogVisible = false">Cancel</el-button>
      <el-button type="primary" @click="dialogVisible = false"
        >Confirm</el-button
      >
    </span>
  </el-dialog>
</template>

<script>
export default {
  props: {},
};
</script>

<style lang="sass" scoped></style>
