<template>
  <h1>Tasks</h1>
</template>

<script setup>
const layout = "task";
definePageMeta({
  layout: "task-layout",
});
useHead({
  title: "Tasks",
  meta: [
    {
      hid: "description",
      name: "description",
      content: "Tasks page",
    },
    {
      hid: "keywords",
      name: "keywords",
      content: "tasks, page",
    },
  ],
});
</script>

<style lang="scss" scoped></style>
