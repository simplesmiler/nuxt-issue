<template>
  <div>Item #{{ $route.params.itemId }} page</div>
</template>

<script>
  export default {
    mounted () {
      alert('/pages/items/' + this.$route.params.itemId + ' was mounted')
    },
    beforeDestroy () {
      alert('/pages/items/' + this.$route.params.itemId + ' is about to be destroyed')
    }
  }
</script>
