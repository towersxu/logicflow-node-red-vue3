<template>
  <div ref="container">11</div>
</template>

<script>
import LogicFlow from "@logicflow/core";

export default {
  name: "LogicFlow",
  props: {
    msg: String,
  },
  mounted() {
    // this.lf = new LogicFlow({
    //   container: this.$refs.container,
    //   width: 500,
    //   height: 500,
    //   grid: {
    //     visible: true,
    //     size: 20,
    //   },
    // });
    // this.lf.render();
  },
};
</script>
<style scoped>
</style>
