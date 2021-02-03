<template>
  <div>
    <svg-icon icon-class="github" @click="goto"/>
  </div>
</template>

<script>
export default {
  name: 'mmGit',
  data() {
    return {
      url: 'https://gitee.com/y_project/mm-Vue'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>
