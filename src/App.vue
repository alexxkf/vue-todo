<template>
  <div id="app"></div>
</template>

<script>
export default {
  name: 'App',
  components: {},
  data() {
    return {
      todos: [
        {
          id: 1,
          Title: 'Todo One',
          completed: false
        },
        {
          id: 2,
          title: 'Todo Two',
          completed: true
        },
        {
          id: 3,
          title: 'Todo Three',
          completed: true
        }
      ]
    };
  }
};
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.4;
}
</style>
