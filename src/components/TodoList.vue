<template>
  <div>
    <h1>{{ title }}</h1>
    <h2>hello</h2>
  </div>
</template>

<script>
export default {
  name: 'TodoList',
  props: {
    title: String,
  },
};
</script>
