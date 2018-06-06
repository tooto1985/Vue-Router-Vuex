<template>
  <div class="t1">
      {{title}}
  </div>
</template>

<script>
module.exports = {
  name: 'mytest',
  data() {
    return {
      title: 'mytest'
    }
  }
}
</script>

<style scoped>
  .t1 {
    color: red;
  }
</style>
