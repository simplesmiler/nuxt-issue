<template>
  <div>
    <nuxt></nuxt>
  </div>
</template>

<script>
  export default {
    mounted () {
      alert('/pages/items was mounted')
    },
    beforeDestroy () {
      alert('/pages/items is about to be destroyed')
    }
  }
</script>
