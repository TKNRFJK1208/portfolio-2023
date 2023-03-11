<script setup>
const { toTitleCase } = useUtilities();

useHead({
  title: toTitleCase('home'),
})

</script>

<template>
  <div>
    <Test />
  </div>
</template>