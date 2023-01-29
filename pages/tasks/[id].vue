<template>
  <h1 class="text-blue-500 bg-red-500 font-bold text-[30px]">{{ id }} test</h1>
</template>

<script setup>
const { id } = useRoute().params;
</script>

<style lang="scss" scoped></style>
