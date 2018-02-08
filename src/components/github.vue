<template>
  <div>
    <p>GitHub文件浏览器</p>
    <span>Full Repo Name: </span>
    <input type="text">
    <button>get your repo!</button>
    <list></list>
  </div>
</template>

<script>
  import list from "./list.vue"
    export default {
        name: "github",
      components: {
          list
      }
    }

</script>

<style scoped>

</style>
