<template>
  <div>{{ title }}</div>
</template>

<script>
let app
export default {
  name: 'vue测试',
  data() {
    return {
      title: 'vue测试',
    }
  },
  computed: {},
  methods: {},
  created() {
    app = this
    console.log(app.title)
  },
}
</script>
