<template>
  <div class='title'>
    <p>{{title}}</p>
    <p>{{subtitle}}</p>
  </div>
</template>

<script>
export default {
  props: ['title', 'subtitle']
}
</script>
<style scoped>
  .title {
    color: 'red';
  }

</style>
