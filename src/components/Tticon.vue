<template>
  <div>
    <i class="toutiao"  :classs="'toutiao-'+name"></i>
  </div>
</template>

<script>
export default {
  props: {
    name: {
      type: String,
      require: true
    }
  },
  created () { },
  data () {
    return {}
  },
  methods: {},
  computed: {},
  watch: {},
  filters: {},
  components: {}
}
</script>

<style scoped>
</style>
