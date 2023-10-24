<template>
  <div>
    <counter></counter>
    <todo-list></todo-list>
  </div>
</template>

<script>
import Counter from './components/Counter.vue'
import TodoList from './components/TodoList.vue'

export default {
  components: {
    Counter,
    TodoList
  }
}
</script>
