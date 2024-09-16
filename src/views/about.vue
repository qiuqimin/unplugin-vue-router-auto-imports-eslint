<script setup>
definePage({
  meta: {
    key: 'value'
  }
})

const route = useRoute()
console.log('route.meta.key:', route.meta.key)
</script>

<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
