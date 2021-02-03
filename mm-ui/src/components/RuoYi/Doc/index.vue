<template>
  <div>
    <svg-icon icon-class="question" @click="goto"/>
  </div>
</template>

<script>
export default {
  name: 'mmDoc',
  data() {
    return {
      url: 'http://doc.mm.vip/mm-vue'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>
