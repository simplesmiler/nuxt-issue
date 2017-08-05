<template>
  <div>
    <h3>Steps:</h3>
    <ol>
      <li>Go to <nuxt-link to="/items/1">/items/1</nuxt-link>.</li>
      <li>Refresh the page, see <code>mounted</code> called.</li>
      <li>Go to <nuxt-link to="/items/2">/items/2</nuxt-link>, see <code>mounted</code> called second time.</li>
      <li>Go to <nuxt-link to="/items/3">/items/3</nuxt-link>, see <code>mounted</code> never called again.</li>
    </ol>
    <nuxt/>
  </div>
</template>
