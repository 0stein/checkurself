<template>
  <div class="container">
    <card-layout>
      <template slot="content">
        <add-todo></add-todo>
        <todo-list></todo-list>
      </template>
    </card-layout>
  </div>
</template>

<script>
import CardLayout from './CardLatyout'
import AddTodo from '../add-todo/AddTodo'
import TodoList from '../todo-list/TodoList'

export default {
  components: {
    CardLayout,
    AddTodo,
    TodoList
  }
}
</script>

<style>

</style>