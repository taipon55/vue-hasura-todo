<template>
  <v-app>
    <div>
      <template>
        <TodoHeader />
      </template>
      <template>
        <TodoList title="TodoList" />
      </template>
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
