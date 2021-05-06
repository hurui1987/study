<template>
  <li class="text">{{ todo.text }}</li>
</template>

<script>
export default {
  name: 'TodoItem',
  props: {
    todo: Object
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.text {
  color: #42b983 
}
</style>
