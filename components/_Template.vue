<template lang="pug">
.template
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'YourComponent',
  components: {},
  validate(context) {
    console.log('context', context)
    return true // if the params are valid
    // return false // will stop Nuxt.js to render the route and display the error page
  },
  // asyncData(context, callback) {},
  props: {},
  data() {
    return {}
  },
  computed: {},
  watch: {},
  created() {},
  mounted() {},
  methods: {}
})
</script>
<style lang="stylus" scoped></style>
