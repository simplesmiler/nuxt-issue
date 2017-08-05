<template>
  <div>Item #{{ $route.params.itemId }} page</div>
</template>

<script>
  export default {
    asyncData() {
      console.log('asyncData of _itemId');
      return {};
    },
    mounted () {
      alert('/pages/items/_itemId was mounted')
    }
  }
</script>
