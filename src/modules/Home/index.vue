<!-- Home -->
<template>
  <div class="home">
    <div class="title">title</div>
    <div class="content">content</div>
    <v-app id="inspire">
      <carousel :colors="colors"/>
    </v-app>
  </div>
</template>

<script>
import carousel from '@componentsDif/Home/carousel'

export default {
  name: '',
  components: {
    carousel
  },
  data () {
    return {
      colors: [
        'primary',
        'secondary',
        'yellow darken-2',
        'red',
        'orange'
      ]
    }
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
