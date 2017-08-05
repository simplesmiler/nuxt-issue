<template>
  <div>
    <h3>Steps:</h3>
    <ol>
      <li>Go to <nuxt-link to="/items/1">/items/1</nuxt-link>.</li>
      <li>Refresh the page, see <code>mounted</code> called for both components.</li>
      <li>Go to <nuxt-link to="/items/2">/items/2</nuxt-link>, see <code>beforeDestroy</code> and then <code>mounted</code> called for both components (instances are not reused).</li>
      <li>Go to <nuxt-link to="/items/3">/items/3</nuxt-link>, see no more hooks called again (instances are reused).</li>
    </ol>
    <nuxt/>
  </div>
</template>
