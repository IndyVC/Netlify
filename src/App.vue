<template>
  <div id="app">
    <div class="container">
      <addTodo />
      <filterTodo />
      <todos />
    </div>
  </div>
</template>

<script>
import todos from "./components/todos.vue";
import addTodo from "./components/addTodo";
import filterTodo from "./components/filterTodos";

export default {
  name: "App",
  components: {
    todos,
    addTodo,
    filterTodo
  }
};
</script>

<style>
body {
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, Helvetica,
    sans-serif;
  line-height: 1.6;
  background: #e8f7f0;
}

.container {
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
</style>
