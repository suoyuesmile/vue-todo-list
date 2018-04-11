<template>
  <div class="helper">
    <span class="left">
      2 item left
    </span>
    <span 
    class="tabs"
    v-for="state in states"
    :key="state"
    :class="[state, filter == state ? 'active' : 'completed']"
    @click="toggleFilter"
    >
      {{state}}
    </span>
  </div>
</template>

<script>
export default {
  data() {
    return {
      states: ['all', 'active', 'completed']
    }
  },
  methods: {
    toggleFilter() {},
    
  }
}
</script>
