<template>
  <div class="t1">
      {{title}}
      <button @click="addCount">AddCount</button>
  </div>
</template>

<script>
module.exports = {
  name: "mytest",
  data() {
    return {
      title: "mytest"
    };
  },
  methods: {
    addCount () {
      this.$store.dispatch('addCount')
    }
  }
};
</script>

<style scoped>
.t1 {
  color: red;
}
</style>
