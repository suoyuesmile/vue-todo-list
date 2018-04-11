<template>
  <div id="app">
    <div id="cover">
      <Header></Header>
      <Todo></Todo>
      <Footer></Footer>
      
    </div>
  </div>
</template>

<script>
import Header from './todo/header.vue'
import Footer from './todo/footer.jsx'
import Todo from './todo/todo.vue'
import Item from './todo/item.vue'
import Tabs from './todo/tabs.vue'

export default {
  data() {
      return {
    }
  },
  components: {
    Header,
    Footer,
    Todo
  }
}
</script>

<style>

</style>