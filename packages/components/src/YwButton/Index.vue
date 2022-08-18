<script>
import { Button } from "element-ui";
export default {
  name: "YwButton",
  data() {
    return {};
  },
  props: {},
  components: {
    ElButton: Button,
  },
};
</script>

<template>
  <el-button class="YwButton">button</el-button>
</template>

<style lang="less" scoped>
.YwButton {
}
</style>
