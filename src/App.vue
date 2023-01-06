<template>
  <v-app>
    <v-app-bar app color="blue" dark>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <v-app-bar-title >TodoList</v-app-bar-title>
    </v-app-bar>
  <div>
    <img alt="Vue logo" src="./assets/logo.png">
    <TodoList title="TodoList" />
  </div>
</v-app>
</template>

<script>
import TodoList from './components/TodoList.vue';

export default {
  name: 'App',
  components: {
    TodoList
}
}
</script>


