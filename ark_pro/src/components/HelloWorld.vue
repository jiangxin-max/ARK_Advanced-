<template>
  <div class="hello">
    <div class="msg">{{ msg }}</div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" scoped>
.hello {
  .msg {
    color: red;
  }
}
</style>
