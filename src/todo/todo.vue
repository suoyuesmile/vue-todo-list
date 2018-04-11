<template>
  <section class="real-app">
    <input type="text" class="add-input" autofocus="autofocus" placeholder="what to to" @keyup.enter="addTodo">
  </section>
</template>

<script>
import Item from './item.vue'
import Tabs from './tabs.vue'

export default {
  data() {

  },
  methods: {
    todo: function() {

    }
  },
  components: {
    Item,
    Tabs
  }
}
</script>

<style>
.real-app {
  /* background: #fff; */
  margin: 0 auto;
  padding-left: 100px;
  width: 400px;
  height: 60px;
}
.add-input {
  width: 400px;
  height: 50px;
  font-size: 24px;
}
</style>
