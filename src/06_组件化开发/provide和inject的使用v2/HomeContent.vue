<template>
  <div>
    {{name}}--{{age}}
  </div>
</template>

<script>
  
  export default {
    inject: ['name', 'age']
  }
</script>

<style scoped>

</style>