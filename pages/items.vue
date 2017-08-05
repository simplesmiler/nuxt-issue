<template>
  <div>
    <nuxt></nuxt>
  </div>
</template>

<script>
  export default {
    mounted () {
      alert('/pages/items was mounted')
    }
  }
</script>
