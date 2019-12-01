<!-- carousel -->
<template>
  <v-carousel
    :show-arrows="showArrows">
    <v-carousel-item
      v-for="(color, i) in colors"
      :key="color"
    >
      <v-sheet
        :color="color"
        height="100%"
        tile
      >
        <v-row
          class="fill-height"
          align="center"
          justify="center"
        >
          <div class="display-3">Slide {{ i + 1 }}</div>
        </v-row>
      </v-sheet>
    </v-carousel-item>
  </v-carousel>
</template>

<script>
export default {
  name: '',
  components: {},
  data () {
    return {
      showArrows: false
    }
  },
  props: {
    colors: {
      type: Array,
      required: true
    }
  },
  computed: {},
  methods: {},
  created () {}
}
</script>
<style lang='scss' scoped>
</style>
