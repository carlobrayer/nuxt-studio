<script setup>
const { data } = await useAsyncData('home', () => queryContent('/').findOne())
</script>

<template>
  <div>

    <H1>test</H1>
    <pre>
      {{ data }}

      {{ data }}
    </pre>
  </div>
  
  
</template>