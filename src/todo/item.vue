<template>
  <div>
    <input 
    type="checkbox" 
    class="toggle"
    v-model="todo.completed"
    >
    <label for="">{{todo.content}}</label>
    <button
    class="destory"
    @click="deleteItem"
    ></button>
  </div>
</template>

<script>
export default {
  props: {
    todo: {
      type: Object,
      required: true
    }
  },
  methods: {
    deleteItem() {

    }
  }
}
</script>

<style>
  
</style>

