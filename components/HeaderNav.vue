<template>
  <nav class="flex items-center mt-4 p-4 rounded-xl bg-gray-100">
    <nuxt-link to="/" class="text-lg font-bold mr-auto">Task Management App</nuxt-link>
    <ul class="flex">
      <li v-for="(item, index) in navItems" :key="index">
        <nuxt-link :to="item.path" class="py-2 px-4 inline-block rounded-xl">
          {{ item.name }}
        </nuxt-link>
      </li>
    </ul>
  </nav>
</template>

<script setup>
const navItems = [
  {
    name: "Home",
    path: "/",
  },
  {
    name: "Tasks",
    path: "/tasks",
  },
  {
    name: "About",
    path: "/about",
  },
];
</script>

<style lang="scss" scoped>
nav ul .router-link-active {
  background-color: #86efac;
}
</style>
