<!-- Home -->
<template>
  <div class="home">
    <div class="title">title</div>
    <div class="content">content</div>
  </div>
</template>

<script>
export default {
  name: '',
  components: {},
  data () {
    return {}
  },
  computed: {},
  methods: {},
  created () {}
}
</script>
<style lang='scss' scoped>
.home {
  .title {
    color: $--founder-default-color;
    font-size: $--founder-title-size;
  }
  .content {
    color: $--founder--color-900;
    font-size: $--founder-content-size;
  }
}
</style>
