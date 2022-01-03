<template>
  <div>
    <h2>this is popup </h2>
    <button @click="$emit('close','bulkin')">close popup</button>
  </div>
</template>

<script>
export default {
    name: 'Popup',
    emits: ['close']
}
</script>

<style>

</style>