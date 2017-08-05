<template>
  <div>Item #{{ $route.params.itemId }} page</div>
</template>

<script>
  export default {
    mounted () {
      alert('/pages/items/_itemId was mounted')
    }
  }
</script>
