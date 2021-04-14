<template>
  <div>
    <ul>
      <li>{{ book.title }} : {{ book.author }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "BookItem",
  props: {
    book: {
      type: String,
    },
  },
};
</script>

<style scoped>
li {
  display: block;
  margin: 0 10px;
}
</style>