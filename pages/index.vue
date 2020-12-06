<template lang="pug">
.home
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  // asyncData(context, callback) {},
  props: {},
  data() {
    return {}
  },
  computed: {},
  watch: {},
  created() {
    console.log('this', this.$content())
  },
  mounted() {},
  methods: {}
})
</script>

<style lang="stylus"></style>
