<template>
  <v-app>
    <div>
      <v-main>
        <v-btn>追加</v-btn>
      </v-main>
    </div>
  </v-app>
</template>

<script>
export default {
  name: 'TodoList',
  props: {
    title: String,
  },
};
</script>
