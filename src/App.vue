<template>

  <div id="app">
  <AddTodo/>
  <FilterTodos/>
  <Todos/>
  </div>

</template>

<script>

import AddTodo from './components/AddTodo.vue'
import Todos from '@/components/Todos'
import FilterTodos from '@/components/FilterTodos'

export default {
  name: 'App',
  components: { 
    AddTodo,
    Todos,
    FilterTodos
  }
}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
