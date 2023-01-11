<template>
  <v-app>
    <div>
      <TodoList title="TodoList" />
      <TodoHeader />
    </div>
  </v-app>
</template>

<script>
import TodoList from './components/TodoList.vue';
import TodoHeader from './components/TodoHeader.vue';

export default {
  name: 'App',
  components: {
    TodoList,
    TodoHeader,
  },
};
</script>
