<template>
  <h1 class="title">{{ msg }}</h1>
  <button class="btn" @click="count++">count is: {{ count }}</button>
  <p>Edit <code>components/HelloWorld.vue</code> to test hot module replacement.</p>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      count: 0
    }
  }
}
</script>

<style lang="css" scoped>
  .title {
    font-size: 40px;
    color: #333;
  }
  .btn {
    border: 1px solid #ddd;
    background: #eee;
    padding: 10px 30px;
    border-radius: 4px;
  }
</style>
