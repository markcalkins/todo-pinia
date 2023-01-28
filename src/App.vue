<script setup>
import TodoApp from './components/TodoApp.vue'
</script>

<template>
  <todo-app />
</template>

<style>
* {
  margin: 0;
  padding: 0;
}
#app {
  background-color: #597d9a;
  display: flex;
  justify-content: center;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
input {
  margin: 0 15px 15px 50px;
  padding: 5px 10px;
}
button {
  padding: 7px 14px;
  background-color: #008CFF;
  border: none;
  color: white;
}
</style>
