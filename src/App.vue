<script>
  export default {
    data() {
      return {
        name: "Welcome to Hampus Portfolio",
        link: "https://github.com/HampusTuisku"
      }
    }
  }
</script>

<template>
  <h1>{{ name }}</h1>
  <a v-bind:href="link">GitHub</a>
</template>

<style>
</style>

